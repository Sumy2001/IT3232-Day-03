# E-Commerce REST API (Spring Boot)
## Overview

This project is a Spring Boot-based REST API for an e-commerce application. 
It provides endpoints to manage various e-commerce functionalities such as user management, products, orders, and more.

## Features

- User authentication and authorization
- Product management (CRUD operations)
- Order processing
- RESTful API endpoints
- Spring Data JPA integration
- H2 Database for development/testing

## API Endpoints

| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | `/products` | Get all products |
| POST | `/products` | Add a new product |
| GET | `/products/{id}` | Get product by ID |
| PUT | `/products/{id}` | Update product |
| DELETE | `/products/{id}` | Delete product |
| POST | `/orders` | Create a new order |

## Project Structure
![Screenshot (59)](https://github.com/user-attachments/assets/a352d4a6-abdf-4ee6-94d3-2c03cd27bc15)

## Student Model

- regNo (String) – Registration Number
- name (String) – Student Name
- age (Integer) – Student Age
- course (String) – Course Name
- gpa (Double) – Grade Point Average

## Running the Application
1. Clone the repository
2. Build using Maven/Gradle
3. Run the Spring Boot application
4. Access endpoints via http://localhost:8080/app/...

## Future Enhancements

- Add database integration
- Implement error handling
- Support POST, PUT, and DELETE requests

