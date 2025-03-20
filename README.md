🔹 Overview
This project is a secure RESTful API built using Node.js, Express.js, SQLite, and Sequelize ORM. It provides user authentication (signup/login with JWT) and product management features while implementing security best practices to prevent attacks like SQL Injection, XSS, and brute force attacks.

🔹 Features
User Authentication (JWT-based)
User signup with email & hashed password.
User login with JWT token authentication.
Protected routes using authentication middleware.
Product Management : 
Create, read, update, and delete products.
Products stored in an SQLite database using Sequelize ORM.
Security Measures : 
Password hashing using bcryptjs.
JWT token authentication for secure access.
Input validation to prevent SQL Injection & XSS attacks.
Database Integration :
Uses SQLite as the database.
Sequelize ORM manages models & relationships.
RESTful API Endpoints :
POST /register – Create a new user.
POST /login – Authenticate user & return JWT token.
GET /products – Retrieve all products (protected).
POST /products – Add a new product (protected).
PUT /products/:id – Update product (protected).
DELETE /products/:id – Delete product (protected).

Technologies Used
Backend: Node.js, Express.js
Database: SQLite with Sequelize ORM
Security: JWT, bcryptjs
Middleware: Express JSON parsing, authentication middleware

How to Run the Project
1️⃣ Install Dependencies
npm install
2️⃣ Run the Server
node server.js
3️⃣ Test API Using Postman or Curl
