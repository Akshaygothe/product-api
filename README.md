# Product API

A RESTful API for managing products using Spring Boot.

## Setup
1. Clone the repo: `git clone <your-repo-url>`
2. Update `application.properties` with your MySQL credentials.
3. Build: `mvn clean install`
4. Run: `mvn spring-boot:run` or from IDE.

## Endpoints
- GET /products: List all products
- GET /products/{id}: Get product by ID
- POST /products: Create product (JSON body)
- PUT /products/{id}: Update product
- DELETE /products/{id}: Delete product

All endpoints require Basic Auth: username "user", password "password".

## Swagger
Access docs at http://localhost:8080/v3/api-docs
UI at http://localhost:8080/swagger-ui.html

## Database
Uses MySQL. Create DB `productdb`.