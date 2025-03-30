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

