# Microservices  Infraestructure 

los microservicios tienen distintas formas en las cuales pueden correr y las cuales han hecho que se bifurque la concepcion del concepto ya sea por que se pueden correr ya sea en Dockers, Lambdas, EC2 o en esquemas serverless (SQS,SNS,S3,Google Functions, etc...)

En lo que nos centraremos para este curso es conocer la arquitectura y ser abstractos en el *Como* para entender el *Por que*.


## Docker
 * Docker

## Orchestation 
 * Docker swarm

## Request Handling
 * Load Balancer
 * Reverse Proxy
 * [Round Robbin](GLOSSARY.md)
 * [Least Conection](GLOSSARY.md)
 * [IP Hash](GLOSSARY.md)

## Deployment
 * blue & green
 * Canary release
 * Feature Flags

## Versioning
 * Semver
 * Protocol Version

## Monitoring
 * Monitor services running Inside them
 * [Service performance](https://thenewstack.io/five-principles-monitoring-microservices/)

## Failure tolerance
 * [Circuit Braker](https://www.reactivedesignpatterns.com/patterns/circuit-breaker.html)
 * [Le-it-crash](https://www.reactivedesignpatterns.com/patterns/let-it-crash.html)
