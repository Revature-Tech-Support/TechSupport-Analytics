# TechSupport-Analytics
Where analytical reports of issue handling are created from the chat application


## Client Specifications:
- Test Driven Development (TDD)


## Goal:
Reports that detail:
   1. Issues resolved per Tech Support Specialist
   2. Average wait time per issue
   3. Average resolution time per issue
   

## User Stories:
### Tech Support
- As a Tech Support
- I want analytical reports
- So that I can optimize our internal support process


## Technology:
- Java
- Lombok
- Spring Boot
- Spring Webflux
- Spring Cloud Netflix
- JUnit 5
- Karate
- Logback classic (SLF4J)
- Maven
- Reactor Netty
- Cassandra


## Endpoints:
- GET `localhost:8080/analysis/resolved`
- GET `localhost:8080/analysis/resolved/{uuid}`
- GET `localhost:8080/analysis/wait`
- GET `localhost:8080/analysis/resolveTime`
