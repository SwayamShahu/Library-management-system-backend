# Library Management System (Backend)

A backend Library Management System developed using **Spring Boot** that provides RESTful APIs to manage books, authors, students, library cards, and book transactions such as issue and return operations.

This project follows a clean **layered architecture** and demonstrates real-world backend development practices using Spring Boot and JPA.

---

## 🚀 Features

- Book, Author, Student, and Library Card management
- Book issue and return functionality
- RESTful CRUD APIs
- Layered architecture (Controller, Service, Repository)
- DTO-based data transfer
- Exception handling and validation
- Status management using enums
- Automatic API documentation using SpringDoc OpenAPI

---

## 🛠️ Tech Stack

- **Java 21**
- **Spring Boot 4.0.1**
- **Spring Data JPA**
- **Hibernate ORM**
- **MySQL**
- **Maven**
- **Spring Validation**
- **SpringDoc OpenAPI**

---

## 📂 Project Structure
```
src/main/java
└── com.example.library
├── controller
├── service
├── repository
├── model
├── dto
├── enums
└── exception
```


---

## 🔗 API Modules

- **Book APIs**
  - Add / Update / Delete / Get books
- **Author APIs**
  - Manage author details
- **Student APIs**
  - Register and manage students
- **Library Card APIs**
  - Issue and manage library cards
- **Transaction APIs**
  - Issue and return books with validations

---

## 📑 API Documentation

After running the application, access Swagger UI:
http://localhost:8080/swagger-ui.html


---

## ⚙️ Setup & Run

### Prerequisites
- Java 21+
- MySQL
- Maven

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/library-management-system-backend.git
2. Configure MySQL in application.properties:
```
spring.datasource.url=jdbc:mysql://localhost:3306/library_db
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```
3. Run the application:
```
mvn spring-boot:run
```
---
🎯 Learning Outcomes

Hands-on experience with Spring Boot backend development

Implemented real-world business logic and validations

Designed REST APIs following best practices

Worked with JPA entity relationships and DTO patterns

---
📌 Future Enhancements

Spring Security with JWT authentication

Role-based access control (Admin / Librarian / Student)

Pagination and sorting

Unit and integration testing
