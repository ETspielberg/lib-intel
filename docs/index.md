# Lib:Intel

Lib:Intel is a platform offering a range of tools for libraries to maintain their stock by evidence based stock management (EBMS).

At its core it is a Spring Boot based microservice architeture, whose central components consist of a Eureka discovery service, a secured config server and a Zuul inversed proxy gateway.
New services can easily be integrated by registering to the central service registry and making them available under a distinct route within the reversed proxy.

The main instruments are the Ausleihprotokoll, the stock analyzer and the counter retrieval tool.
The connection to the library system is performed py the so called getter client.

## Verwendete Techniken

```eval_rst
Spring
    https://spring.io

Spring Boot
    https://spring.io/projects/spring-boot
    
Spring Cloud
    https://spring.io/projects/spring-cloud
    
Spring Security
    https://spring.io/projects/spring-security

Angular 6
    https://angular.io/

PrimeNG
    https://www.primefaces.org/primeng/#/

PostgreSQL
    https://www.postgresql.org/
```

## Frontend Modules
```eval_rst
Gateway
    https://github.com/ETspielberg/gateway

Ausleihprotokoll
    https://github.com/ETspielberg/protokoll-frontend

Admin
    https://github.com/ETspielberg/admin-frontend

Media
    https://github.com/ETspielberg/media-frontend

Fachref
    https://github.com/ETspielberg/fachref-frontend-server
```

## Backend Modules
```eval_rst
Config server
    https://github.com/ETspielberg/config

Service discovery
    https://github.com/ETspielberg/service-discovery

Counter-Retrieval
    https://github.com/ETspielberg/counter-retrieval

Stock-Anaylzer
    https://github.com/ETspielberg/stockanalyzer

Scripts
    https://github.com/ETspielberg/libintel_scripts

Getter
    https://github.com/ETspielberg/manifestationgetter

Ausleihprotokoll
    https://github.com/ETspielberg/protokoll-frontend
```





## Angular Frontends
```eval_rst
Gateway
    https://github.com/ETspielberg/gateway-ui

Ausleihprotokoll
    https://github.com/ETspielberg/protokoll

Admin
    https://github.com/ETspielberg/admin

Media
    https://github.com/ETspielberg/media-management

Fachref
    https://github.com/ETspielberg/fachref-frontend

```





