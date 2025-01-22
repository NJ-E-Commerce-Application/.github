## Hi there 👋
# Microservices E-commerce Platform

## Description

This is a microservices-based e-commerce platform designed to manage products, inventory, and orders using independent microservices. The platform provides scalability, maintainability, and robust fault tolerance, making it suitable for modern e-commerce applications. 

The system is secured using **Keycloak** for authentication and authorization, and requests are streamlined through an **API Gateway**. Additionally, the project includes API documentation with **OpenAPI** and uses a **Circuit Breaker** pattern for enhanced reliability.

## Key Features

### 1. **Product Service**
- Allows creation and management of products.
- Enables viewing all available products in the system.

### 2. **Inventory Service**
- Checks product availability using SKU code.
- Manages product quantities in the inventory.

### 3. **Order Service**
- Handles order placement by checking inventory for product availability.
- Saves the order once the product is available in the inventory.

### 4. **API Gateway**
- Implemented using **Spring Cloud Gateway MVC** for managing and routing requests between microservices.
- Provides load balancing and efficient communication between services.

### 5. **Security**
- All microservices are secured using **Keycloak** for centralized authentication and authorization.

### 6. **API Documentation**
- REST APIs are documented using **OpenAPI** to facilitate integration and usage.

### 7. **Fault Tolerance**
- Integrated **Circuit Breaker** to gracefully handle failures and ensure service reliability.

## Technologies Used
- **Spring Boot** (for developing microservices)
- **Spring Cloud Gateway** (for API Gateway)
- **Keycloak** (for authentication and authorization)
- **OpenAPI** (for API documentation)
- **Circuit Breaker** (for fault tolerance)
- **Docker** (for containerization)
- **JPA/Hibernate** (for database interaction)
