#python #sintaxis #programacion_y_afines #lenguajes_de_programacion #personal 
## Tipos de datos
- ### Numéricos:
	- #int
		- Valores números enteros $\to$ 3
	- #float
		- Representa números con punto decimal o punto flotante (Números reales)$\to$ 3.0
- ### Texto:
	- #str o #string 
		- Representa secuencias o cadenas de caracteres $\to$  ""
- ### Lógicos:
	- #bool
		- Representa valores binarios $\to$ True/False
---------
## Operaciones
#operaciones
- ### Operadores aritméticos
	- + ${} \to$ Suma
	- / ${} \to$ División 
	- -${} \to$ Resta
	- * $\to$ Multiplicación
	- ** $\to$ Potenciación
	- // $\to$ División entera
	- % $\to$ Modulo
	- $\to$ Inverso 
- ## Operadores de comparación
- son aplicables para int y float y siempre retornan un valor booleano
	- < $\to$ menor que
	- > $\to$ mayor que
	- <= $\to$ menor o igual que
	- >= $\to$ mayor o igual que
	- == $\to$ comparación
	- != $\to$ distinto a 
- ### Operadores Lógicos 
	- NOT $\to$ Hace que cualquier proposición cambie su valor lógico 
	- AND $\to$ Todos lo valores deben ser verdaderos para dar verdadero
	- OR $\to$  Cuando un valor es verdadero, todo es verdadero
- ### Operadores para Strings
	- + $\to$ Concatenación $\to$ string +string
	- * $\to$ Repetición $\to$ string * int
----
## Conversiones entre datos 
#datos
No tienen muchos problemas entre las operaciones entre #int y #float, esto debido a que Python permite fácilmente estas operaciones.

En cambio si ponemos la siguiente expresión, Python detectara un problema
![[Pasted image 20250329155927.png]] 
no permite implícitamente esto..
podemos usar ese int como un string usando esto: 
![[Pasted image 20250329160146.png]]
De esta forma se convierte en un string
Podemos aplicar esta forma en el caso anterior, donde Python no permitía la operación: 
![[Pasted image 20250329160345.png]]
### También existen conversiones de string a float o int
![[Pasted image 20250329160807.png]]
Debemos considerar muy bien el solo convertir strings que en su contenido solo hayan valores numéricos, no como el siguiente caso: 
	![[Pasted image 20250329161614.png]]

-------
## Variables
#variable #variables 
Debemos asignarle un nombre a un valor, los nombres de estos valores son las **Variables**, Python usara el ultimo valor que agregamos. De la siguiente forma:
	![[Pasted image 20250329162635.png]]
El $=$ que usamos tiene la función de asignar este valor a la variable, par que la guarde en la memoria.
Podemos recuperar el valor usando el nombre de la variable.
Si vamos a llamar alguna variable de la memoria, debemos recordar que esta debió haber sido asignada/guardada con anterioridad, de otra forma nos dará el siguiente mensaje: 
	![[Pasted image 20250329163410.png]]
Esto significa que 'radio' no se definió con anterioridad, o que su valor es nulo y no se puede operar.
### Condiciones para nombrar una variable
- **Deben** empezar con una letra o '_'
- De ahí en adelante se puede seguir con letras, números.
- No usar palabras claves/reservadas del sistema como 'not', 'and', 'str', no usar la siguiente lista:
	- ![[Pasted image 20250329163759.png]]
- Tampoco usar símbolos especiales.
----
## Escritura de texto en pantalla print()
Recordemos que el programa esta en el "Backend" y con esta forma podemos dar en un "Output", lo que usamos dentro del Print().
- ### Sintaxis
![[Pasted image 20250329164848.png]]
Funciona de la siguiente forma, siendo lo azul, lo impreso en consola:
![[Pasted image 20250329164943.png]]
La expresión dentro de print, puede ser cualquiera, incluso operaciones o variables.
	![[Pasted image 20250329165018.png]]
También puede imprimir directamente alguna operación aritmética
	![[Pasted image 20250329165101.png]]
También variables que guardan algún valor 
	![[Pasted image 20250329165111.png]]
También puede operar expresiones de comparación e imprimir valores booleanos
	![[Pasted image 20250329165128.png]]
## Escritura lineal o salteada
Podemos emplear instrucciones print() salteadas y estas nos permiten imprimir en distintas líneas, de la siguiente forma:
	![[Pasted image 20250329165546.png]]
También si lo que deseamos es imprimir en la misma línea, se puede de la siguiente forma, usando comas entre las expresiones:
	![[Pasted image 20250329170028.png]]
También existen distintas instrucciones con las expresiones en la misma instrucción **Print()**
- ### end=
	- Con esta instrucción se puede hacer un cambio en el termino de línea, de la siguiente forma
	-  ![[Pasted image 20250329170551.png]] 
- ## sep=str
	- Esta instrucción permite que la separación automática entre expresiones impresas en consola, no sea necesariamente un espacio $\to$ ' ', sino algo determinado por uno mismo como en el siguiente caso:
	- ![[Pasted image 20250329171655.png]]
-----
## Entradas de datos
A partir de la siguiente linea se pueden absorber datos y guardarlos en una variable, esto con el fin de manejar los mismos en el programa del sistema que estemos manejando.
![[Pasted image 20250703104005.png]] 
El "texto" dentro del input, es la pregunta que hará el programa para que el usuario ingrese el dato ![[Pasted image 20250703104633.png]]
este dato que absorbe la variable es tomada como un #string y si haremos alguna operación debemos indicar en el programa la conversión necesaria para su manejo y su correcta interpretación.![[Pasted image 20250703105006.png]] usando el "int()" anidando el "input()" podemos cambiar el tipo de dato que absorberá la variable, aunque siempre debemos tener en consideración que el sistema primero tomara el dato como un #string y no como un #int

Se puede convertir en distintos tipos de datos, esto respecto a lo requerido por el programa
### Int #int
![[Pasted image 20250703105454.png]]
### Float #float
![[Pasted image 20250703105526.png]]
### Bool  #bool
![[Pasted image 20250703105549.png]]

----
## Condicionales
Existen diversos tipos de condiciones dependiendo de cuantas condiciones deba cumplir un programa o la complejidad de las elecciones 
### If #if 
Se usa para condiciones simples o con una solo bloque de operacion al ser "TRUE" la condicion marcada
IMPORTANTE: el programa al no detectar esta condicion simplemente salta el bloque de instrucciones
### If-Else #if #else 
Se usa para condiciones mas complejas y al igual que con el #if el programa hace las instrucciones dentro del bloque interno del #if, pero si la condicion marcada en el #if llega a ser "FALSE" el programa ejecutara el bloque de comando dentro del #else, siendo esto para cualquier caso distinto a la condicion puesta en el #if 
### Elif #Elif 
Es un #if mas complejo desde el cual  el programa puede decidir un flujo de condiciones mas diverso, puede tener dos opciones de acciones y cada una dependiendo de su especifica 
