# 📚 Study Tube – Skill Sharing Platform

Study Tube is a full-stack web application built as a **skill sharing and learning management platform**.  
It allows users to register, login, create learning plans, share posts, and interact with other learners through a structured system.

The backend is built using **Spring Boot REST API with JWT authentication**, and the frontend uses **HTML, Tailwind CSS, and JavaScript**.

---

## 🚀 Project Overview

This system is designed to support collaborative learning by enabling users to:
- Register and login securely
- Create and manage learning plans
- Share posts and resources
- Interact with other users
- Track learning progress

---

## 🏗️ System Architecture

- **Frontend:** HTML, Tailwind CSS, JavaScript  
- **Backend:** Spring Boot (Java)  
- **Security:** JWT Authentication  
- **Database Layer:** Spring Data JPA  
- **Build Tool:** Maven  

---

## 🔐 Authentication System

The system uses **JWT-based authentication** for secure access.

### 📌 Auth Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/auth/register` | Register a new user |
| POST | `/auth/login` | Authenticate user and generate JWT token |

### 📥 Registration
Users can register by sending a request to:

POST /auth/register


Handled by:
- `AuthController.register()`
- Uses `RegisterRequest` DTO
- Returns success or error response

---

### 🔑 Login
Users authenticate using:

POST /auth/login


Handled by:
- `AuthController.authenticate()`
- Uses `AuthRequest` DTO
- Returns JWT token on success

---

### ⚠️ Error Handling
- Global exception handling inside `AuthController`
- Returns meaningful error messages for:
  - Registration failure
  - Authentication failure
  - Internal server errors

---

## ✨ Key Features

### 👤 User Management
- User registration & login
- JWT authentication system
- Secure API access

### 📚 Learning System
- Learning plan creation
- Weekly progress tracking
- Structured learning updates

### 📝 Social Features
- Post creation and sharing
- Resource sharing system

### 💬 Communication
- Messaging system between users

### 🔔 Notifications
- User activity notifications

---

## ⚙️ Backend Technologies

- Java 17+
- Spring Boot
- Spring Security
- JWT (JSON Web Token)
- Spring Data JPA
- Maven
- SLF4J Logging

---

## 🎨 Frontend Technologies

- HTML5
- CSS3
- Tailwind CSS
- JavaScript (Vanilla)

---


---

## 🚀 How to Run the Project

### 🖥️ Backend

1. Open project in IntelliJ / Eclipse
2. Configure `application.yml`
3. Run:

```bash
mvn spring-boot:run

