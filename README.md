# OData corriendo en Java con conexion a MySQL
La finalidad de este repositorio es mostrar una rapida implementacion de **odata** en java e interactuar con ella a traves de una sencilla app en react. Los datos seran guardados en MySQL.

### Tecnologías:
- MySQL
- Java
- Olingo Odata v2
- react


### Despliegue
Esta pensado para correrse en 3 contenedores docker, uno para backend, otro para la DB y otro para el front. Para iniciarlos basta con correr en el directorio *container*:

	sudo docker-compose up


## Uso
Los contenedores docker van a brindar 3 servicios en los siguientes puertos
- http://localhost:8080/odata/MyODataServiceServlet.svc/Books?$format=json  => API Endpoint de Odata
- http://localhost:3003        => MySQL
- http://localhost:3002        => FrontEnd
