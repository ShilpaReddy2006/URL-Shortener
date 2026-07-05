# 🔗 URL Shortener

A full-stack URL Shortener web application built using **Spring Boot**, **Java**, **MySQL**, **JWT Authentication**, and **HTML/CSS/JavaScript**. Users can register, log in securely, generate shortened URLs, and access the original URLs using the generated short links.

## 🚀 Live Demo

### Frontend
https://url-shortener-q8hc.onrender.com

### Backend API
https://url-shortener-backend1-rblx.onrender.com

---

## 📌 Features

- 👤 User Registration
- 🔐 JWT-based User Authentication
- 🔑 Secure Login
- 🔗 Generate Short URLs
- 📋 Copy Short URL with One Click
- 🌐 Redirect to Original URL
- 💾 MySQL Database Integration
- 📱 Responsive User Interface
- 🔒 Password Encryption
- ☁️ Deployed on Render
- 🗄️ Cloud Database using Aiven MySQL

---

## 🛠️ Tech Stack

### Backend
- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- JWT Authentication
- Maven

### Frontend
- HTML5
- CSS3
- JavaScript (ES6)

### Database
- MySQL
- Aiven Cloud MySQL

### Deployment
- Render
- GitHub

---

## 📂 Project Structure

```
URL-Shortener
│
├── Backend
│   ├── src
│   ├── pom.xml
│   └── Dockerfile
│
└── frontend
    ├── css
    ├── js
    ├── images
    ├── index.html
    ├── login.html
    ├── register.html
    └── dashboard.html
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/ShilpaReddy2006/URL-Shortener.git
```

```bash
cd URL-Shortener
```

---

### 2. Backend Setup

Navigate to Backend folder

```bash
cd Backend
```

Run the application

```bash
mvn spring-boot:run
```

---

### 3. Frontend Setup

Open the frontend folder using Live Server or any static web server.

---

## 🔧 Environment Variables

Configure the following environment variables for the backend.

```properties
SPRING_DATASOURCE_URL=
SPRING_DATASOURCE_USERNAME=
SPRING_DATASOURCE_PASSWORD=
PORT=
```

---

## 📖 API Endpoints

### Authentication

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /auth/register | Register User |
| POST | /auth/login | Login User |

---

### URL

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /api/urls | Create Short URL |
| GET | /api/urls/{shortCode} | Redirect to Original URL |

---


## 🔒 Authentication

The application uses **JWT (JSON Web Token)** authentication.

After successful login:

- JWT Token is generated.
- Token is stored in browser Local Storage.
- Protected API requests include the JWT token in the Authorization header.

---

## 🌍 Deployment

### Frontend
- Render Static Site

### Backend
- Render Web Service

### Database
- Aiven MySQL

---

## 🚀 Future Enhancements

- URL Analytics
- Click Counter
- QR Code Generation
- Custom Short URLs
- URL Expiration
- User Profile
- Edit/Delete URLs
- Dashboard Statistics

---

## 👩‍💻 Author

**Shilpa Reddy**

GitHub:
https://github.com/ShilpaReddy2006

LinkedIn:
https://www.linkedin.com/in/yerravalla-shilpa-reddy-0266272a5?utm_source=share_via&utm_content=profile&utm_medium=member_android
---

## ⭐ Support

If you like this project, please consider giving it a ⭐ on GitHub.

---

