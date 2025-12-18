# Classwork 1: Customer Service with GraphQL

## Activity: Micro-service Fundamentals & GraphQL

This project demonstrates a Spring Boot microservice with REST API and GraphQL support.

## Features
- REST API with CRUD operations
- GraphQL queries and mutations
- Spring Data JPA with H2 Database
- Lombok for boilerplate reduction
- SpringDoc OpenAPI for documentation

## Project Structure
```
customer-service/
├── src/main/java/net/atertour/customerservice/
│   ├── entities/Customer.java
│   ├── repository/CustomerRepository.java
│   ├── service/CustomerService.java
│   └── web/CustomerRestController.java
└── src/main/resources/
    ├── application.properties
    └── graphql/schema.graphqls
```

## How to Run
```bash
cd customer-service
mvn spring-boot:run
```

## Endpoints
- REST API: `http://localhost:8081/api/customers`
- H2 Console: `http://localhost:8081/h2-console`
- GraphQL Playground: `http://localhost:8081/graphiql`

## Author
Youssef Atertour - EMSI 2025

---

## Proof Screenshots

### REST API Endpoint (Populated)
![Customer REST API showing JSON data](screenshots/rest_api_populated.png)

### Error Handling (Whitelabel Fixed)
![Global Exception Handler - JSON Error](screenshots/error_handling.png)

### H2 Database Console
![H2 Console showing CUSTOMER table data](screenshots/h2_console.png)


