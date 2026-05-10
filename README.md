# Movie Authentication API

A secure and scalable REST API for user authentication and management, built with **Spring Boot**. This project implements modern authentication practices, including **JWT tokens**, refresh token mechanisms, role-based access, and custom exception handling.

Take a Full look at how the features work through these screenshots:
JWT Auth and CRUD: https://lnkd.in/dbfiUttJ
Exception Handling: https://lnkd.in/diNHgr75
Pagination and Sorting: https://lnkd.in/dEJTeiVA
Forgot Password and Reset: https://lnkd.in/dqqyDVWE

## Features
- User registration and login with secure password hashing.
- Role-based access control using `UserRole` (Admin/User).
- JSON Web Token (JWT) authentication and refresh tokens.
- Custom exception handling for better error reporting.
- Validation for user inputs and request payloads.
- MySQL database integration for user data persistence.

## Tech Stack
- **Backend**: Spring Boot (Java), Spring Security
- **Database**: MySQL, JPA/Hibernate
- **Tools**: IntelliJ IDEA, Postman
- **Build**: Maven

## Project Setup
Follow these steps to run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/movieflix-auth-api.git
   cd movieflix-auth-api
   
2.Create a database in MySQL:
  CREATE DATABASE movieflix_db;

3.Update application.properties with your database configuration:

    spring.datasource.url=jdbc:mysql://localhost:3306/movieflix_db
    
    spring.datasource.username=YOUR_USERNAME
    
    spring.datasource.password=YOUR_PASSWORD
    
4. Build and run the project:
   
    mvn clean install
   
    mvn spring-boot:run

5. Test the API using Postman or any REST client.
   




