# 🎥 Full-Stack Video Streaming Web Application

A **full-stack video streaming platform** built using **Spring Boot (Backend)** and **ReactJS (Frontend)**.  
This project allows users to **upload, browse, and stream videos online** securely, just like a mini-YouTube clone.  
It includes **JWT-based authentication**, **REST APIs**, and **Docker support** for easy deployment.

---

## 🚀 Features

✅ User registration & login using JWT Authentication  
✅ Video upload with metadata (title, description, etc.)  
✅ Real-time streaming using HTTP Range requests  
✅ REST APIs for managing videos & users  
✅ Responsive and clean UI built with ReactJS  
✅ MySQL Database Integration  
✅ Docker-based setup for easy deployment  

---

## 🏗️ Tech Stack

### 🔹 Backend
- **Spring Boot**
- **Spring Web / Spring MVC**
- **Spring Security with JWT**
- **MySQL Database**
- **Lombok**, **JPA**, **Hibernate**
- **Maven**

### 🔹 Frontend
- **ReactJS**
- **Axios**
- **React Router**
- **TailwindCSS / Bootstrap**
- **HTML5 Video Player**

### 🔹 Deployment / Tools
- **Docker**
- **Postman**
- **VS Code / Eclipse**
- **Git & GitHub**

---

## 🧩 Project Architecture
<img width="556" height="610" alt="image" src="https://github.com/user-attachments/assets/61aec1c0-d862-49c6-8d0d-7a5f6a2b5f33" />


---

## ⚙️ Setup Instructions

### 🖥️ Backend Setup
1. Open the project in **IntelliJ IDEA** or **VS Code**.
2. Create a MySQL database named `videostream_db`.
3. Update your `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/videostream_db
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   spring.jpa.hibernate.ddl-auto=update


