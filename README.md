<center> 
  <h1>Microservices Crash Course</h1>
</center>
<p align="center">
  <img width="auto" height="600" src='https://www.mypatentprints.com/wp-content/uploads/2016/06/communication-satellite-patent-space-art-space-poster-space-program-rockets-aircraft-decor-aviation-art-blueprint-pilot-gift-5750f2531.jpg'>
</p>

### Introduccion
Crash Course de Microservicios escritos con Golang y desplegados en Docker por la comunidad de [Glosbe learners online](https://www.meetup.com/es-ES/Glosbe-Developers-online/).
La intencion de este curso es explicar la arquitectura de microservicios de la forma mas simple posible poniendo en practica los patrones mas comunes y estudiandolos a fondo mediante proyectos.

## Indice:

1.- [Introduccion](microservice-definition)
  * ¿Que es un Microservicio? 
  * Definicion de Microservicio
    * Ventajas
    * Desventajas
    * Patrones
    * Antipatrones
    * ¿Por que Golang? 

2.- [Composición de un Micro servicio](microservice-composition)
  * Comunicación
  * Seguridad
  * Cache
  * Monitoreo
  * Business logic

3.- [Tecnicas Devops de mantenimiento, deployment](microservice-infraestructure)
  * Dockers
  * Orchestation
  * Request Handling
  * Deployment
  * Monitoring
  * Versioning
  * Failure Tolerance
  

4.- [Implementacion de Patrones](microservice-patterns)
  * Projects
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
      - Photo Manager 
    * Gateway Aggregation
    * Gateway Offloading
    * Gateway Routing
    * [Sidecar](https://blog.davemdavis.net/2018/03/13/the-sidecar-pattern/)
    * Strangler
    * Event Driven
    * [Saga](https://blog.bernd-ruecker.com/saga-how-to-implement-complex-business-transactions-without-two-phase-commit-e00aa41a1b1b)
    * [Observer](https://hackernoon.com/observer-vs-pub-sub-pattern-50d3b27f838c#8bf1)
    * [PubSub](https://hackernoon.com/observer-vs-pub-sub-pattern-50d3b27f838c#49d0)