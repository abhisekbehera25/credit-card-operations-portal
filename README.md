💳 Credit Card Operations Portal

A cloud-native Credit Card Operations Portal developed using Spring Boot Microservices and React, designed to simulate real-world credit card operational workflows.
The application is fully containerized and deployed on AWS using CI/CD pipelines, demonstrating end-to-end full-stack and DevOps skills.

🚀 Project Overview

This project follows microservices architecture to ensure scalability, maintainability, and cloud readiness.
It covers backend services, frontend UI, database integration, and AWS deployment.

Key Highlights:

Backend built with Spring Boot Microservices

Frontend developed using React

CI/CD implemented using GitHub + AWS CodeBuild & CodeDeploy

Containerized with Docker

Deployed on AWS ECS

Frontend hosted on AWS S3

Database hosted on AWS RDS (PostgreSQL)

🧩 Architecture

API Gateway – Central entry point for all client requests

Service Discovery – Dynamic service registration and discovery

Microservices – Independent Spring Boot services for business logic

Frontend (React) – User interface for credit card operations

Database – PostgreSQL on AWS RDS

CI/CD Pipeline – Automated build and deployment

This architecture ensures loose coupling, scalability, and high availability.

🛠️ Tech Stack
Backend

Java

Spring Boot

Spring Cloud (Microservices)

REST APIs

Docker

Frontend

React

JavaScript

HTML5, CSS3

Database

PostgreSQL (AWS RDS)

Cloud & DevOps

AWS ECS

AWS S3

AWS RDS

AWS CodeBuild

AWS CodeDeploy

GitHub

🔄 CI/CD & Deployment Flow

Code pushed to GitHub

AWS CodeBuild builds the application and Docker images

Docker images pushed to container registry

AWS ECS deploys backend microservices

Frontend build uploaded to AWS S3

Application connects to PostgreSQL on AWS RDS

This ensures automated, reliable, and scalable deployments.

▶️ How to Run Locally
Prerequisites

Java 17+

Node.js

Docker

PostgreSQL

Steps
git clone https://github.com/<your-username>/credit-card-operational-portal.git
cd credit-card-operational-portal
docker-compose up

🔐 Security & Best Practices

Secrets and credentials are not committed to GitHub

Environment variables managed using .env files

Production-ready folder structure

Dockerized microservices

Cloud-native deployment approach

📸 Screenshots

(Add screenshots of the UI and AWS deployment here to increase recruiter impact)

👨‍💻 Author

Abhisek Behera
Java Full Stack Developer | Spring Boot Microservices | AWS | Docker | React

📌 This project is built to demonstrate real-world enterprise application development and deployment.

🔥 Recruiter Tip

This project demonstrates:

Full Stack Development

Microservices Architecture

Cloud Deployment (AWS)

CI/CD & DevOps Practices
