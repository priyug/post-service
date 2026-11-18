This project is a Spring Boot Microservices-based application consisting of three independent services: User Service, Post Service, and Notification Service.
The services communicate with each other using REST APIs and RestTemplate for synchronous inter-service communication. 
The application demonstrates how multiple microservices interact to retrieve and manage related data using a unique User ID.

Post Service
Manages user-related post information.
Exposes REST APIs to retrieve posts based on User ID.
Provides post details to other microservices.

Key Features
Independent microservices architecture.
Synchronous inter-service communication using RestTemplate.
REST API-based data exchange.
Dynamic data retrieval using User ID.
Aggregation of data from multiple microservices.
Separation of business responsibilities across services.
