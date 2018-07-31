# Microservices

### Que es un Microservicio?

Esta es una pregunta donde muchas personas difieren entre si, ya que diferentes usos de la arquitectura han generado variantes las cuales tienen patrones y antipatrones muy marcados que llegan a ser confusos para quien quiere tener una concepcion de la tecnologia la definicion que hoy voy a dar de microservicio es para aquel publico que esta iniciando y asi mismo le ayude a entender que son y cual es la razon de ser de estos.

### Microservicio

Es una arquitectura que busca dividir las funcionalidades de un sistema entero en pequeños segmentos que tienen la habilidad de comunicarse entre si, operar descentralizada y autonomamente.

Los beneficios mas visibles de esto son:

* Escalabilidad 
* Redundancia
* Performance
* Autonomia
* Reusabilidad de Codigo

Las desventajas son las siguientes

* Dificil monitoreo
* Complejidad al implementar pruebas 
* Sistemas transaccionales

### Patrones

Los patrones de diseño son formas en las que se puede emplear cierta tecnologia que dictan como solucionar un problema de manera optima.
Patrones de diseño presentes en los microservicios:

* API GATEWAY
* Agregattor
* Proxy 
* Chained
* Branch
* Shared data
* Asynchronous
* Anti-corruption layer
* Backends for Frontends
* Bulkhead
* Gateway Aggregation
* Gateway Offloading
* Gateway Routing
* Sidecar
* Strangler
* Event Driven
* Saga
* Observer
* PubSub

### Como se compone un Microservicio ? 

Los microservicios a nivel macro se componen de patrones a nivel micro se pueden entender como un conjunto de funciones que realizan una o una serie de acciones, normalmente los microservicios funcionan bajo el principio de comunicacion, Decentralizacion y Automatizacion dicho esto podemos asumir que dichos servicios tienen como base:

* Endpoints que permiten la entrada de datos desde otros microservicios.
* Bibliotecas de comunicacion con base de datos.
* Bibliotecas que se encarga de enviar datos.
* Capa de procesamiento (business logic).
* Biblioteca de Despliegue, Monitoreo para conocer el estado.



#### Resources
* [patterns I ](http://blog.arungupta.me/microservice-design-patterns/)
* [patterns II](https://vslive.com/Blogs/News-and-Tips/2018/02/Go-Fast-by-Going-Micro-Microservices-Design-Patterns-You-Should-Know.aspx)
* [intro microservices](https://www.nginx.com/blog/introduction-to-microservices/)
