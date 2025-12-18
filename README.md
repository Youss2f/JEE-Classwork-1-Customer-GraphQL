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

## Project Demo

### Customer API Endpoint
![Customer API Response](screenshots/customer-api-list.png)

### Global Exception Handling
![API Error Response](screenshots/api-error-response.png)

### Database Console (H2)
![H2 Console](screenshots/h2-database-console.png)



