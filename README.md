🏦 Credit Card Operations Portal

Spring Boot Microservices | React | AWS | Docker | PostgreSQL

A production-ready Credit Card Operations Portal built using Spring Boot Microservices and React, deployed on AWS using Docker, ECS, CI/CD pipelines, and PostgreSQL (RDS).
This project demonstrates real-world enterprise architecture, security, and cloud deployment.

🚀 Project Highlights (Recruiter First Look)

✅ Microservices Architecture (5 services)

✅ JWT Authentication & Role-Based Authorization

✅ Real-Time Transaction Processing

✅ Dockerized & Cloud Deployed

✅ CI/CD using GitHub + AWS CodeBuild & CodeDeploy

✅ Frontend hosted on AWS S3

✅ Database per service (PostgreSQL – RDS)

🧩 System Architecture
Client (React)
     |
API Gateway (JWT, Routing)
     |
------------------------------------------------
| Auth | Customer | Card | Transaction Services |
------------------------------------------------
     |
PostgreSQL (RDS – DB per service)


API Gateway – Central entry point, JWT validation

Auth Service – Authentication & token management

Customer Service – Customer lifecycle management

Card Service – Credit card issuance & balance handling

Transaction Service – Purchases, refunds, payments

🛠️ Technology Stack
Backend

Java 17

Spring Boot & Spring Cloud

Spring Security (JWT)

OpenFeign (inter-service communication)

Frontend

React

HTML, CSS, JavaScript

DevOps & Cloud

Docker & Docker Compose

AWS ECS (Backend)

AWS S3 (Frontend)

AWS RDS (PostgreSQL)

AWS CodeBuild & CodeDeploy

GitHub

🔐 Key Features
Authentication & Security

JWT-based authentication

Role-based access control (ADMIN, CUSTOMER)

Secure password encryption (BCrypt)

Credit Card Management

Issue cards (Silver / Gold / Platinum)

Card activation, blocking & expiry

Credit limit & daily limit enforcement

Transactions

Purchases, refunds, payments

Real-time balance updates

Transaction history & analytics

🔄 CI/CD & Deployment Flow

Code pushed to GitHub

AWS CodeBuild builds Docker images

Images deployed to AWS ECS

Frontend build deployed to AWS S3

PostgreSQL hosted on AWS RDS

✔ Fully automated deployment pipeline

▶️ Run Locally (Quick Start)
git clone https://github.com/<your-username>/credit-card-operations-portal.git
cd credit-card-operations-portal
docker-compose up --build


Services will be available via API Gateway at:

http://localhost:8080

📖 API Documentation

Swagger UI:

Auth Service → http://localhost:8084/swagger-ui.html

Customer Service → http://localhost:8081/swagger-ui.html

Card Service → http://localhost:8082/swagger-ui.html

Transaction Service → http://localhost:8083/swagger-ui.html

📁 Project Structure
credit-card-operations-portal/
├── backend/
│   ├── api-gateway
│   ├── auth-service
│   ├── customer-service
│   ├── card-service
│   └── transaction-service
│
├── frontend/
│   └── credit-card-portal-ui
│
├── docker-compose.yml
├── README.md
└── .gitignore

☁️ Cloud Deployment

Backend deployed on AWS ECS

Frontend hosted on AWS S3

Database on AWS RDS (PostgreSQL)

This project is cloud-ready and scalable for production use.

👨‍💻 Author

Abhisek Behera
Java Full Stack Developer | Spring Boot Microservices | AWS | Docker | React

🔗 GitHub: https://github.com/abhisekbehera25

🔗 LinkedIn: https://www.linkedin.com/in/abhisekbehera225/
