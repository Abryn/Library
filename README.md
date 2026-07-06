# Library REST API

A simple but clean RESTful API built in Java and Spring Boot for managing a book library. \
Built as a hands-on project to demonstrate modern backend development, explore Spring Boot, and REST API design.

## Features
- Full CRUD operations (create, read, update, delete)
- Input validation with Jakarta Bean Validation
- Global error handling using `@ControllerAdvice`
- H2 in-memory database with Spring Data JPA

## Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/books` | Get all books |
| GET | `/books/{id}` | Get a book by ID |
| POST | `/books` | Create a new book |
| PUT | `/books/{id}` | Update a book |
| DELETE | `/books/{id}` | Delete a book |

## Tech Stack
- Java 21
- Spring Boot 3.3.5
- Spring Data JPA / Hibernate
- H2 Database
- Maven

## Running the project
1. Clone the repo
2. Run `LibraryApplication.java`
3. API is available at standard `http://localhost:8080`