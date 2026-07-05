# Booking App (Backend)

This repository contains the backend REST API for the Booking system. It is built using Java Spring Boot and provides secure data management, authentication, and services for the frontend applications.

## Related Repository

- **Frontend Application:** [Project PAB - Frontend](https://github.com/rzhfXV/projectpab-frontend/tree/ver1.2)

## Tech Stack

- **Language:** Java 21
- **Framework:** Spring Boot (Web MVC)
- **Database:** MySQL
- **ORM / Data Access:** Spring Data JPA
- **Security:** Spring Security & JWT (JSON Web Tokens)
- **Utilities:** Lombok, Commons FileUpload

## Prerequisites

- Java Development Kit (JDK) 21
- Maven (or use the included Maven wrapper `mvnw`)
- MySQL Server

## Setup & Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/rzhfXV/projectpab-backend/tree/experimental
   ```
2. Open the project in your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse, or VS Code).
3. Create a MySQL database for the project (you can use the included `.sql` file to import the database structure).
4. Update the `src/main/resources/application.properties` (or `.yml`) file with your MySQL database credentials.
5. Let Maven resolve and download all required dependencies.
6. Run the application via your IDE or by using the Maven wrapper:
   ```bash
   ./mvnw spring-boot:run
   ```

## Authors

- [Malika Shalshabila Auralina](https://github.com/mlkasha)
- [Raihan Zhafran Fadhil](https://github.com/rzhfXV)
