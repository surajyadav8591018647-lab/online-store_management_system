Online Store Management System

A full-stack Online Store Management System built using React, Java, Spring Boot, and MySQL.

The application allows users to browse products, view product details, add products to their cart, and place orders. Administrators can manage products, categories, inventory, and customer orders.

Features

User

- User registration and login
- Browse available products
- Search and filter products
- View product details
- Add products to cart
- Update or remove cart items
- Place orders
- View order history
- User dashboard

Admin

- Admin login
- Add, update, and delete products
- Manage product categories
- View all products
- Manage product inventory
- View customer orders
- Update order status
- Role-based authorization

Technologies Used

Frontend

- React
- JavaScript
- Axios
- React Router
- HTML5
- CSS3
- Vite

Backend

- Java
- Spring Boot
- Spring Web
- Spring Security
- JWT Authentication
- Spring Data JPA
- Hibernate
- Maven

Database

- MySQL

Project Structure

Online-store-management-system/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   ├── api.js
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   ├── src/
│   │   └── main/
│   │       ├── java/
│   │       │   └── [application packages]
│   │       └── resources/
│   │           └── application.properties
│   ├── pom.xml
│   └── mvnw
│
└── README.md

Installation and Setup

1. Clone the Repository
cd Online-store-management-system

2. Backend Setup

- Open the "backend" folder in IntelliJ IDEA.
- Configure the MySQL database in "application.properties".
- Install Maven dependencies.
- Run the Spring Boot application.

3. Frontend Setup

cd frontend
npm install
npm run dev

4. Database Configuration

Update your MySQL database settings in "application.properties":

spring.datasource.url=jdbc:mysql://localhost:3306/online_store
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

Learning Outcomes

- Developed RESTful APIs using Spring Boot.
- Implemented product and inventory management functionality.
- Integrated React frontend with backend REST APIs.
- Designed database entities and relationships using MySQL and JPA.
- Implemented user authentication and role-based access control.
- Gained practical experience in full-stack application development.

