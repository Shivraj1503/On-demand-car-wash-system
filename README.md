# On-Demand Car Wash System

The On-Demand Car Wash System is a microservices-based application developed using Spring Boot. 
It allows users to register, log in securely, add car details, and book car wash services through a simple and user-friendly flow.

## Tech Stack
- Java
- Spring Boot
- Spring Security (JWT)
- REST APIs
- Eureka Server
- API Gateway
- MySQL
- JPA / Hibernate
- Razorpay (Payment Integration)
- Swagger
- JUnit 5 & Mockito

## Features
- User authentication and authorization using JWT
- Role-based access for users, admin and washer
- Admin:- To add and update, delete the washer
- User:- Booking of car and payment
- Washer:- To collect and proceed the order and view ratings 
- Secure online payment integration
- Microservices architecture with service discovery
- API documentation using Swagger

## Architecture
The system follows a microservices architecture with independent services such as User Service, Booking Service, Payment Service, and Admin Service, connected through an API Gateway and registered with Eureka Server.

