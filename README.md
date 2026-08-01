# 🍽️ DineFlow

**DineFlow** is a full-stack Restaurant Management System developed using **Java, Spring Boot, Spring MVC, Spring Data JPA (Hibernate), Thymeleaf, and MySQL**. The application streamlines restaurant operations by providing efficient customer, inventory, and order management with secure authentication and role-based access control.

---

## 🚀 Features

### 👥 Customer Management

* Add, update, view, and delete customer records
* Manage customer details efficiently

### 📦 Inventory Management

* Track food items and stock availability
* Update inventory quantities
* Maintain product pricing

### 🛒 Order Management

* Create and manage customer orders
* Update order status
* View complete order history

### 🔐 Authentication & Authorization

* Secure login system
* Role-based access control (Admin & Staff)
* Protected application routes

### 💾 Database Integration

* MySQL database for persistent storage
* Spring Data JPA (Hibernate) for ORM
* Automatic CRUD operations

### 🎨 Responsive User Interface

* Dynamic web pages using Thymeleaf
* Clean and user-friendly interface
* HTML, CSS, and JavaScript integration

---

## 🛠️ Technology Stack

### Backend

* Java 8
* Spring Boot
* Spring MVC
* Spring Data JPA (Hibernate)

### Frontend

* Thymeleaf
* HTML5
* CSS3
* JavaScript

### Database

* MySQL

### Build Tool

* Maven

### IDE

* Spring Tool Suite (STS)
* Eclipse

---

## 📋 Prerequisites

Before running the project, ensure the following are installed:

* Java 8 or above
* MySQL
* Maven
* Eclipse / Spring Tool Suite (STS)

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/DineFlow.git
```

### 2. Navigate to the Project

```bash
cd DineFlow
```

### 3. Configure MySQL

Create a database named:

```sql
CREATE DATABASE dineflow;
```

Update the `application.properties` file:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/dineflow
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true
```

### 4. Build the Project

```bash
mvn clean install
```

### 5. Run the Application

```bash
mvn spring-boot:run
```

or run the main Spring Boot application directly from your IDE.

---

## 🌐 Access the Application

Open your browser and visit:

```
http://localhost:8080
```

---

## 📁 Project Structure

```text
src
├── main
│   ├── java
│   │   └── com.example.dineflow
│   │       ├── controller
│   │       ├── model
│   │       ├── repository
│   │       ├── service
│   │       └── config
│   ├── resources
│   │   ├── templates
│   │   ├── static
│   │   └── application.properties
│   └── webapp
│       └── WEB-INF
│           └── views
└── test
```


## 🎯 Key Highlights

* Layered Architecture (Controller → Service → Repository)
* Spring MVC Design Pattern
* Hibernate ORM for database operations
* Secure Authentication & Authorization
* CRUD Operations
* Responsive UI with Thymeleaf
* MySQL Database Integration
* Clean and Maintainable Code Structure

---

## 🔮 Future Enhancements

* Payment Gateway Integration
* Email Notifications
* Sales & Revenue Dashboard
* REST API Support
* Docker Deployment
* Cloud Hosting
* QR Code Menu
* Online Table Reservation

---

## 👨‍💻 Author

Developed as a **Full-Stack Java Web Application** using Spring Boot and MySQL to demonstrate enterprise-level application development with secure authentication, database integration, and modern Java frameworks.

---

## ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub.
