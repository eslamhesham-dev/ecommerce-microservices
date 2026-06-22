# E-Commerce Microservices

This project is a basic e-commerce microservices application built using Spring Boot and Spring Cloud.

The goal of this project is to practice microservices architecture concepts such as centralized configuration, service discovery, API gateway routing, and service-to-service communication.

## Services

The project contains the following services:

```text
ecommerce-microservices/
│
├── config-server
├── eureka-server
├── api-gateway
├── product-service
├── inventory-service
├── order-service
└── payment-service
```

## Main Components

### Config Server

Provides centralized configuration for all microservices using Spring Cloud Config.

### Eureka Server

Provides service discovery so microservices can register themselves and discover each other.

### API Gateway

Acts as the main entry point for client requests and routes them to the correct microservice.

### Product Service

Manages products and product information.

### Inventory Service

Manages product stock and availability.

### Order Service

Handles customer orders and communicates with inventory and payment services.

### Payment Service

Handles payment processing logic for orders.

## Technologies

* Java
* Spring Boot
* Spring Cloud
* Spring Cloud Config
* Eureka Discovery Server
* Spring Cloud Gateway
* Spring Data JPA
* PostgreSQL
* Maven

## Current Goal

The first goal is to build the basic setup and connect all services using Spring Cloud Config.
