#universidad #api #rest #ingenieria_de_software #VI_semestre 
Son la forma para realizar solicitudes y respuestas en un #api #rest 
1. GET: Obtiene datos
2. POST: Crear datos
3. PUT: Actualiza datos
4. DELETE: Elimina datos
Esto es basicamente un #crud 
----

| tipo de metodo                | metodo  | uso                                |
| ----------------------------- | ------- | ---------------------------------- |
| SAFE METHODS                  | GET     | metodo mas usado                   |
| Sin accion en el servidor     | HEAD    | inspecciona headers                |
| MESSAGE WITH BODY             | PUT     | deposita informacion al servidor   |
| Envia informacion al servidor | POST    | envia datos para procesar          |
|                               | PATCH   | modificacion parcial de un recurso |
|                               | TRACE   | eco de recepcion de mensajes       |
|                               | OPTIONS | capacidades del servidor           |
|                               | DELETE  | elimina un recurso                 |

-----
Siempre el frontend debe tener consiencia de los metodos a mover en el #api 


----
### Estructura solicitud #rest 
- URL : Direccion del recurso solicitado
- Metodo HTTP: 
	- GET 
	- PUT 
	- POST 
	- DELETE 
- Encabezados: Información adicional, como el tipo de contenido de la petición
- Cuerpo: Datos enviados en una solicitud
----

