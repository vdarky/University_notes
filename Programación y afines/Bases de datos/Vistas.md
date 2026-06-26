#bases_de_datos #universidad #V_semestre 
- Consulta almacenada que presenta los datos de una o mas tablas en una estructura similar a una tabla real
- Se conoce también como tabla virtual $\text{VISTAS}\to \text{TABLAS VIRTUALES}$

## CARACTERISTICAS
- *No almacenan datos*: Solo guardan la consulta, no los datos en si.
- *Seguridad y control de acceso*: se pueden usar para restringir que columnas o filas pueden ver ciertos usuarios.
- *Facilitan consultas complejas*: se pueden crear vistas para simplificar consultas complicadas
- Se pueden usar como si fueran una tablas: Se pueden realizar $SELECT$ y en algunos casos $INSERT$, $UPDATE$ y $DELETE$

## TIPOS DE VISTAS
- Vistas simple: Basadas en una sola tabla sin funciones agregadas
- Vistas complejas: Basadas en múltiples tablas con $JOINS$ o agregaciones
- Vistas materializadas

## SINTAXIS PARA CREAR UNA VISTA
CREATE VIEW nombre_vista 
SELECT columna1, columna2, …
FROM

### También se pueden modificar las vistas o eliminar


| Ventajas                                                                | Desventajas                                         |
| ----------------------------------------------------------------------- | --------------------------------------------------- |
| permiten simplificar consultas complejas                                | Algunas vistas no permiten actualizaciones directas |
| mejoran la seguridad al restringir el acceso a ciertas columnas o filas | En bases de datos grandes                           |
|                                                                         |                                                     |
