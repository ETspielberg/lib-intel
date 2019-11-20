# Lib:Intel 

![Lib:Intel logo](figures/logo/logo_libintel.png "Lib:Intel")


Lib:Intel is a platform offering a range of tools for libraries to maintain their stock by evidence based stock management (EBMS).

At its core it is a Spring Boot based microservice architeture, whose central components consist of a Eureka discovery service, a secured config server and a Zuul inversed proxy gateway.
New services can easily be integrated by registering to the central service registry and making them available under a distinct route within the reversed proxy.

The main instruments are the Ausleihprotokoll, the stock analyzer and the counter retrieval tool.
The connection to the library system is performed py the 'getter client'.

## Verwendete Techniken

The complete framework allows for a large number of techniques to be incorporated. Up to know, the following techniques have been used:

* [Spring](https://spring.io)
* [Spring Boot](https://spring.io/projects/spring-boot)
* [Spring Cloud](https://spring.io/projects/spring-cloud)
* [Spring Security](https://spring.io/projects/spring-security)
* [Angular 6](https://angular.io/)
* [PrimeNG](https://www.primefaces.org/primeng/#/)
* database, e.g. [PostgreSQL](https://www.postgresql.org/)
    

## Major backbone

A handful of services are required and form the backbone of the Lib:Intel-platform. They are responsible for the configuration, the service-discovery (Eureka-Client) and the reversed Proxy (Gateway).  

* [Gateway](https://github.com/ETspielberg/gateway)
* [Config server](https://github.com/ETspielberg/config)
* [Service discovery](https://github.com/ETspielberg/service-discovery)
 

## Current list of available frontends

A number of frontends have been developed and are included into the platform as microservices. They all consist of  [Spring Boot](https://spring.io/projects/spring-boot) Web Server, incorporated into the overall [Spring Security](https://spring.io/projects/spring-security) system. Each retreives the configuration properties from the central config server and registers at the central Eureka server.

* [Ausleihprotokoll](https://github.com/ETspielberg/protokoll-frontend)
* [Admin](https://github.com/ETspielberg/admin-frontend)
* [Media](https://github.com/ETspielberg/media-frontend)
* [Fachref](https://github.com/ETspielberg/fachref-frontend-server)
* in preparation: [Glossar]
* in preparation: [SDG Analysis](https://github.com/Aurora-Network-Global/sdg-analysis-frontend)


## Current list of backend modules
The backends provide the services made accessible by the frontends or direct calls to the corresponding APIs. They are mainly Spring Boot based and incorporate Spring Batch Modules as well. Data are made available through RESTful repositories.

* [Counter-Retrieval](https://github.com/ETspielberg/counter-retrieval)
* [Stock-Anaylzer](https://github.com/ETspielberg/stockanalyzer)
* [Getter](https://github.com/ETspielberg/manifestationgetter)
* [Linksolver-Wrapper](https://github.com/ETspielberg/linksolver-wrapper)
* [Elisa-Connector](https://github.com/ETspielberg/elisa-connector)
* [Settings](https://github.com/ETspielberg/settings-backend)
* [Blcklist](https://github.com/ETspielberg/blacklist-backend)
* in preparation: [Scripts](https://github.com/ETspielberg/libintel_scripts)
* in preparation: [Bibliometrics](https://github.com/Aurora-Network-Global/sdg_query_execution)







