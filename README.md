# 📚 English Course - Backend

Backend REST API for the English Course Platform developed with Spring Boot.

The system provides authentication, course management, lesson management, quiz functionality, and user progress tracking.

---

## 🚀 Tech Stack

- Java 21
- Spring Boot
- Spring Security
- JWT Authentication
- Spring Data JPA
- MySQL
- Maven

---

## ✨ Features

- User Authentication
- JWT Authorization
- Course Management
- Lesson Management
- Quiz Management
- User Progress Tracking
- RESTful APIs

---

## ⚙️ Installation

### Clone repository

```bash
git clone https://github.com/LTV1103/English-Course-BE.git
```

### Configure database
1. Create a new MySQL database.

```sql
CREATE DATABASE english_course_test;
```

2. Import the SQL file located in the project.

```
db_english_course_test.sql
```

### .env
Before running the application, create a `.env` file in the project root and configure the following environment variables.

### Required Environment Variables

```env
# Database
DB_URL=jdbc:mysql://localhost:3306/english_course
DB_USERNAME=root
DB_PASSWORD=your_password

# JWT
JWT_SECRET=your_jwt_secret
JWT_EXPIRATION=86400000
JWT_EXPIRATION_REFESH=604800000

# Google OAuth2
GOOGLE_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

# VNPay
TMN_CODE=your_tmn_code
HASH_SECRET=your_hash_secret
PAY_URL=https://sandbox.vnpayment.vn/paymentv2/vpcpay.html
RETURN_URL=http://localhost:8080/payment/vnpay-return

# Cloudinary
CLOUD_NAME=your_cloud_name
API_KEY=your_api_key
API_SECRET=your_api_secret
```

## Run the application

```bash
mvn clean install
mvn spring-boot:run
```

The backend will start at:

```
http://localhost:8080
```


### Run project

```bash
mvn spring-boot:run
```

Server will start at

```
http://localhost:8080
```

---

<!-- ## 📖 API Documentation

Swagger

```
http://localhost:8080/swagger-ui/index.html
```

(if enabled)

--- -->

## 🔗 Frontend Repository

Frontend source code:

👉 https://github.com/LTV1103/English-Course-FE

---

## 👨‍💻 Author

LTV1103
