
### Como se compone un Microservicio ? 

Visto desde nivel macro se componen de patrones a nivel particular se pueden entender como un conjunto de funciones que realizan una o una serie de acciones de una sla entidad, normalmente los microservicios funcionan bajo el principio de comunicacion, decentralizacion, tolerancia a fallos, redundancia, etc.

#### Comunicación:

Los micro servicios comunmente se comunican mediante bibliotecas que se basan en estos patrones:

* Requests
	* REST
	* SOAP
	* RPC

* Events

Todos estos pueden ser [Sincronos](../microservice-definition/GLOSSARY.md) o [Asincronos](../microservice-definition/GLOSSARY.md).


#### Seguridad

Oauth, JWT, Session Handling, Role Handling, Permission Handling.

#### Cache

Uno de los puntos mas fuertes sobre el perfomance de un servicio esta basada en el cache, el cache puede ser una de las piezas clave para sistemas con alta demanda de datos y/o consultas.

#### Monitoreo/Logueo

El monitoreo de estos microservicios es una parte importante para conocer el estado y la degradacion de estos para poder observar irregularidades que afecten el performance del proceso.

Para esto tenemos librerias tales como:
* NATS
* New Relic

Que permiten capturar system failures, system performance, service latency entre otros.

#### Business logic

Como parte de un microservicio la funcionalidad es la constante que debe orquestar todos los demas componentes de forma adecuada.