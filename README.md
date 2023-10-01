
# Ecommerce application

## Frameworks and Language Used
- Framework: Spring Boot
- Language: Java
- Database: MySQL

## Data Flow

### Controller
- The controllers handle incoming HTTP requests and route them to the appropriate service methods.
- They are responsible for receiving input, validating requests, and sending responses.
- Examples: UserController, ProductController, OrderController

### Services
- Service classes contain the business logic of the application.
- They interact with repositories to perform CRUD operations and other operations.
- Services process data and prepare it for presentation in the controllers.
- Examples: UserService, ProductService, OrderService

### Repository
- Repositories provide an interface to interact with the database.
- They use Spring Data JPA to perform CRUD operations on the database tables.
- Examples: UserRepository, ProductRepository, OrderRepository

### Database Design
- The database design consists of several tables corresponding to entity models.
- It includes tables for User, Product, Address, and Order entities.
- Relationships such as foreign keys are established to maintain data integrity.

## Data Structures Used
- The project utilizes standard Java data structures like lists, arrays, and maps for in-memory data manipulation.
- Additionally, Spring Data JPA handles database operations using entity objects.

## Project Summary
- This Ecommerce Application is built using Spring Boot and Java.
- It allows users to perform CRUD operations on User, Product, Address, and Order entities.
- The project follows a structured architecture with controllers, services, and repositories.
- Data is stored in a MySQL database with appropriate relationships.
- The API is designed to handle user registration, product management, order placement, and more.