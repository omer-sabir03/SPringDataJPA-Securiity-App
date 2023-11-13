# Spring Security Bank Application
This is a basic Spring Boot application implementing security features for a simplified bank application. It includes user authentication, authorization, and basic banking operations.

## Features

- User registration and login.
- Secured endpoints for banking operations (e.g., view account balance).
- Role-based access control for different user roles (e.g., user, admin).

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Java installed
- Maven installed
- Database (e.g., MySQL) set up with the appropriate configuration in `application.properties`.

## Configuration

Update the `application.properties` file with the necessary database and security configuration:

```properties
# Database Configuration
spring.datasource.url=jdbc:mysql://localhost:3306/bankapp
spring.datasource.username=
spring.datasource.password=

