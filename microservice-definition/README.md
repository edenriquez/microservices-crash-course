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
* [Service Degradation](https://blog.risingstack.com/designing-microservices-architecture-for-failure/#gracefulservicedegradation)
* Reusabilidad de Codigo

Las desventajas son las siguientes:

* Dificil monitoreo
* Complejidad al implementar pruebas 
* Sistemas transaccionales
* Mantenimiento

### [Patrones](GLOSSARY.md)

Los patrones de diseño son formas en las que se puede emplear cierta tecnologia que dictan como solucionar un problema de manera optima.
Patrones de diseño presentes en los microservicios:

* API Gateway
* Agregattor
* Proxy 
* Chained
* Branch
* Shared data
* [Asynchronous](https://dzone.com/articles/patterns-for-microservices-sync-vs-async)
* [Adapter service](https://hackernoon.com/learning-these-5-microservice-patterns-will-make-you-a-better-engineer-52fc779c470a#fb1c)
* Anti-corruption layer
* Backends for Frontends
* [Bulkhead](https://blog.risingstack.com/designing-microservices-architecture-for-failure/#Bulkheads)
* Gateway Aggregation
* Gateway Offloading
* Gateway Routing
* Sidecar
* Strangler
* Event Driven
* [Saga](https://blog.bernd-ruecker.com/saga-how-to-implement-complex-business-transactions-without-two-phase-commit-e00aa41a1b1b)
* [Observer](https://hackernoon.com/observer-vs-pub-sub-pattern-50d3b27f838c#8bf1)
* [PubSub](https://hackernoon.com/observer-vs-pub-sub-pattern-50d3b27f838c#49d0)


### Antipatrones

* [Data Driven Migration](https://www.oreilly.com/ideas/microservices-antipatterns-and-pitfalls)
* [Functionaly First, Data Last](https://www.oreilly.com/ideas/microservices-antipatterns-and-pitfalls)
* [The Timeout AntiPattern](https://www.oreilly.com/ideas/microservices-antipatterns-and-pitfalls)
* [Using the Circuit Breaker Pattern](https://blog.risingstack.com/designing-microservices-architecture-for-failure/#circuitbreakers)

### ¿Por que Golang? 

Golang permite intercomunicar pequeños servicios http/https entre si y se tiene mucha de la funcionalidad en el core, entonces muchas veces el mismo lenguaje te puede proveer de las herramientas, con un performancce de una aplicación compilada ademas de los features por los cuales es bien aceptado.

* Concurrency
* Parallelism
* Multithread
* High Level abstraction
* Memory Optimization
* Extensible

### Patrones en Golang

[Patterns](https://github.com/tmrts/go-patterns)


#### Resources
* [patterns I ](http://blog.arungupta.me/microservice-design-patterns/)
* [patterns II](https://vslive.com/Blogs/News-and-Tips/2018/02/Go-Fast-by-Going-Micro-Microservices-Design-Patterns-You-Should-Know.aspx)
* [intro microservices](https://www.nginx.com/blog/introduction-to-microservices/)
* [Message queue patterns](https://www.enterpriseintegrationpatterns.com/patterns/messaging/toc.html)
* [Architecture patterns](https://towardsdatascience.com/10-common-software-architectural-patterns-in-a-nutshell-a0b47a1e9013)
