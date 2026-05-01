# 🏥 DiaCare Backend - Authentication System

## 📌 Project Overview

This repository contains the backend implementation of the **DiaCare platform**, a healthcare system focused on **diabetes management**.

This part of the project focuses on a **multi-role authentication system** with secure account management and validation workflows.

---

## 🚀 Features Implemented

### 🔐 Multi-role Authentication

* Admin
* Patient
* Doctor
* Nutritionist

Each role has its own access logic and permissions.

---

### 📧 Email Verification System

* Users must activate their account via an email link
* Secure token-based activation
* Prevents unauthorized access

---

### 👨‍⚕️ Role Validation Workflow

* Doctors and Nutritionists must:

  * Upload professional certificate (PDF/Image)
  * Wait for **Admin approval**
* Admin can:

  * Approve or reject applications

---

### 🔒 Security

* Spring Security configuration
* Password encryption using BCrypt
* Protected endpoints
* CORS configuration for Angular frontend

---

### 🗂️ Architecture

* Layered architecture:

  * Controller
  * Service
  * Repository
  * Entity
* Clean separation of concerns

---

## 🛠️ Technologies Used

* Java 17
* Spring Boot
* Spring Security
* Hibernate / JPA
* MySQL
* JavaMailSender (Email Service)

---

## ⚙️ API Endpoints (Auth)

| Endpoint                  | Method | Description      |
| ------------------------- | ------ | ---------------- |
| `/api/doctor/auth/signup` | POST   | Register doctor  |
| `/api/doctor/auth/login`  | POST   | Login doctor     |
| `/api/admins/signup`      | POST   | Register admin   |
| `/api/admins/login`       | POST   | Login admin      |
| `/api/.../activate`       | GET    | Activate account |

---

## 📌 Note

This repository contains **my personal contribution** to a group project.

My main responsibility:
👉 Designing and implementing the **authentication and authorization system** for multiple roles.

---

## 👩‍💻 Author

* Jihan Dh
