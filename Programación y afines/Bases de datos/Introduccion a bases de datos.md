#bases_de_datos #universidad #V_semestre #introduccion 
## NO Relacional $\to$ No estrictas

- No existe relación
- Grandes volúmenes de datos

## Relacional (SQL) $\to$ Tablas estrictas

- Existen relaciones entre los datos o tablas

### Operaciones

- Consultas estructuradas de datos

---

$$ \text{Registros } \to \text{Filas }\to \text{Tuplas} $$

$$ \text{Ficheros }\to \text{Centralizada: como excel} $$

---

$$ \text{B.D Relaciones }\to \text{SQL }\to \text{Busca decentralizar las bases de datos o la informacion} $$

$$ \text{S.G.B.D }\to \text{Sistema Gestor de Base de Datos }\to \text{Software Base de datos} $$

---

## Clasificación de acceso de datos

$$ \text{Procedural }\to \text{Registro a registro} $$

$$ \text{NO procedural }\to \text{SQL} \to \text{Todo el conjunto de datos} $$

## Manipulación de datos $\text{C.R.U.D.}$

- Create: Sirve para crear nuevos datos en alguna tabla
- Read: Sirve para capturar el valor ya guardado en algún dato
- Update: Sirve para cambiar o actualizar el valor ya establecido en un dato
- Delete: SIrve para eliminar algún dato

---

$\text{S.G.B.D }\to$

- Seguridad
- Constancia de los datos
- Control de concurrencia
- Recuperación a un punto anterior
- Diccionario de datos
    - En ocasiones es el $MER$

---

Las base de datos surgen en el alunizaje $\to NAA$

$\text{G.U.A.M: General Update Access Method}$

---

El nombre de las bases de datos surgió en $\text{CODASYL: Conference On Data Systems Languages a finales de 1971}$

---

## $MER\to \text{Modelo Entidad Relacion} \to \text{por Peter Chan en 1976}$

El termino entidad en $MER$ es la forma de abstracción por atributos $\to$ información en los parámetros de las tablas y sus relaciones natas

---

## Tipos de datos a manejar

- $ENUM \to$ Lista estándar de datos constantes
- $Int \to$ $\text{4 bytes} \to \text{0 - 4.294.967.285}$
- $Boolean \to F/V$
- $Bigint \to \text{8 bytes}\to \text{ 0 - 16777215 o 0 - -838608}$
- $Float \to$ # Coma flotante
- $Double \to \text{Mas rango}$

### Fechas

- $Date \to Año/Mes/Dia$
    
- $Datetim \to CurrentDateTime$
    
    - $Time\to HH:MM:SS$
    - $Year$
    
    ### Text
    
- $Char \to \text{Cantidades variables}$
    
- $VarChar \to \text{Caracteres fijos en cantidad}$
    
- $\text{Longblob y Blob}\to \text{Imagenes NO tan grandes}$

----
Mas informacion buscar 
[[Bases de datos ddl consulta.pdf]]
[[Funciones de agregacion.pdf]]
[[Procedimientos almacenados (Stored procedures).pdf]]
[[Reglas de integridad bases de datos.pdf]]
[[210927124637-Manual MySQL (1).pdf]]
[[Vistas]]
[[Niveles de abstraccion]]