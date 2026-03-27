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
