# Distributed-E-Commerce-Backend-System
Architected a Microservices based ECommerce Platform with support of core functionalities of any ECommerce Website like Product Catalog, Payment Gateway Integration, Order Service, Notification Service etc.

Below are the repository links of each services 
1. Product Service   - https://github.com/GowthamThangamuthu/Product-Service
2. Payment Service   - https://github.com/GowthamThangamuthu/PaymentService2025
3. User Service      - https://github.com/GowthamThangamuthu/UserService2025
4. Email Service     - https://github.com/GowthamThangamuthu/EmailService-2025
5. API Gateway       - https://github.com/GowthamThangamuthu/APIGateway-2025
6. Service Discovery - https://github.com/GowthamThangamuthu/Service-Discovery2025

Architectural Diagram : https://drive.google.com/file/d/1hWB2G8rUQTWUVRDXUtKyuA2FNfGTwYB8/view?usp=sharing

Tech Stack:
Backend: Spring Boot, Spring Cloud (Eureka, API Gateway)
Messaging: Kafka
Database: MySQL
Caching: Redis
Search: ElasticSearch
Payment: Stripe
Auth: JWT
Testing: JUnit


Microservices feautures of each service : 
Product Service    - Handles product CRUD, search, filtering (ElasticSearch), etc.
User Service       - Handles user registration, login, JWT token generation, role-based access.
Payment Service    - Processes payments using Stripe API.
Email Service      - Kafka-driven email notifications.
API Gateway        - Central routing, authentication validation.
Service Discovery  - Eureka registry for microservice discovery.


⚙️ Setup & Installation
Prerequisites
Install the following:
1. Java 17+
2. MySQL
3. Redis
4. Kafka
5. ElasticSearch
6. Maven

Startup Order :
1. Start Service Discovery (Eureka)
2. Start API Gateway
3. Start User Service
4. Start Product Service
5. Start Payment Service
6. Start Email Service
