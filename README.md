
E-Notes is a simple, user-friendly application built with Spring Boot for managing personal notes.
It provides secure user registration, login, and logout features, along with full CRUD operations for notes.
The frontend is developed using HTML, CSS, JavaScript, and Bootstrap 5, while the backend uses MySQL for data persistence.

Features

User Module

Registration: Allows users to create an account.
Login/Logout: Secure authentication and session management.
Profile Management: Manage user details.

Notes Module
Create Notes: Add new notes with a title and description.
Read Notes: View all notes created by the user.
Update Notes: Edit existing notes.
Delete Notes: Remove notes no longer needed.

Technologies Used
Backend: Spring Boot, Hibernate (JPA), Lombok
Frontend: HTML, CSS, JavaScript, Bootstrap 5
Database: MySQL
Build Tool: Maven

Project Structure
Backend

Entity Layer:
User: Stores user details such as id, username, email, password.
Notes: Stores note details such as id, title, content, and associated userId.


Controller Layer:
Handles HTTP requests for user registration, authentication, and CRUD operations on notes.

Service Layer:
Contains business logic for user and note operations.

Repository Layer:
Uses JPA to interact with the MySQL database.

