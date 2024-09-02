# Publication Management System

## Overview
This project is a Publication Management System built using Spring Boot, providing functionalities to manage publications, authors, and categories. It includes features such as CRUD operations, admin/user login, form validations, MySQL database connectivity, and session management.

## Features
### CRUD Operations
- Manage publications, authors, and categories with Create, Read, Update, and Delete operations.

### Admin and User Login
- Secure endpoints with roles for admin and user access.
- Admin can perform all CRUD operations.
- Users have limited access based on their role.

### Form Validations
- Validate forms for creating and updating publications, authors, and categories to ensure data integrity.

### Database Connectivity to MySQL
- Use MySQL as the backend database to store publication, author, and category information.
- Configure database connection settings in `application.properties`.

### Session Management
- Manage user sessions for authentication and authorization.
- Implement session timeout and secure session handling.

## Technologies Used
- Java 17
- Spring Boot MVC
- Spring Data JPA
- Spring Security
- MySQL Database
- Thymeleaf (or your preferred view technology for frontend rendering)
