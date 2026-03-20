# E-Commerce Backend Application

## Overview

This project is a backend E-Commerce application developed using Spring Boot. It provides core functionalities required for an online shopping system, including product management, user handling, and order processing.

The application is designed using a layered architecture to ensure scalability, maintainability, and separation of concerns.

---

## Features

* CRUD operations for product management
* User data handling
* Order processing functionality
* RESTful API design
* Database integration with MySQL

---

## Tech Stack

* Java
* Spring Boot
* Spring MVC
* Spring Data JPA / Hibernate
* MySQL
* Maven

---

## Architecture

The application follows a standard layered architecture:

* **Controller Layer** – Handles HTTP requests
* **Service Layer** – Contains business logic
* **Repository Layer** – Interacts with database
* **Entity Layer** – Defines data models

---

## Project Structure

```id="x9dk21"
E-commerce-project-springBoot/
│── src/main/java
│── src/main/resources
│── application.properties
│── pom.xml
│── springproject.sql
```

---

## Setup

### Prerequisites

* JDK 8 or above
* Maven
* MySQL

### Steps

1. Clone the repository
2. Configure database in `application.properties`
3. Import `springproject.sql` into MySQL
4. Run:

   ```
   mvn spring-boot:run
   ```
5. Access APIs at:

   ```
   http://localhost:8080
   ```

---

## API Usage

The application exposes REST APIs for:

* Product operations
* User operations
* Order operations

Test using Postman or any API client.

---

## Objective

To implement a scalable backend system demonstrating REST API development, database integration, and structured application design using Spring Boot.

---

## Author

Sneha Jaiswal
B.Tech (Computer Science)

---
