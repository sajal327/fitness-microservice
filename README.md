# 🏋️ AI-Powered Fitness Microservices Platform

A **cloud-native, event-driven fitness application** built using **Spring Boot microservices, Apache Kafka, AI/ML, FastAPI, Docker**, and modern web & mobile clients (**React.js & Flutter**).

This platform captures user fitness activities, processes them asynchronously, and generates **AI-driven personalized recommendations** in real time.

---

## 📌 Architecture Overview

![Architecture Diagram](docs/Architecture.png)


---

## 🚀 Key Features

- Microservices architecture with **Spring Boot**
- **API Gateway** as a single entry point
- **Service Discovery** using Eureka
- **Centralized Configuration** with Spring Cloud Config
- **Event-driven communication** using Apache Kafka
- **AI Recommendation Engine** (FastAPI + ML)
- **Docker-first local development**
- **React.js Web App** & **Flutter Mobile App**
- Scalable and cloud-ready (AWS / Kubernetes)

---

## 🧱 Technology Stack

### Backend
- Java 17
- Spring Boot
- Spring Cloud (Eureka, Config Server, Gateway)
- Spring Data JPA (PostgreSQL)
- Spring Data MongoDB
- Apache Kafka
- WebClient
- FastAPI (AI Service)
- Python (Machine Learning)

### Databases
- PostgreSQL (User data)
- MongoDB (Activity & events)

### Infrastructure
- Docker & Docker Compose
- Git-based Config Repository
- Kafka

### Frontend / Mobile
- React.js (Web)
- Flutter (Mobile)

---

## 🗂️ Project Structure
fitness-ai-microservices/
│
├── api-gateway/
├── config-server/
├── eureka-server/
├── userservice/
├── activityservice/
├── activity-consumer/
├── ai-service/
│   ├── training/
│   └── inference/
│
├── config-repo/
│   ├── application.yml
│   ├── userservice.yml
│   ├── activityservice.yml
│   └── api-gateway.yml
│
├── docker-compose.yml
├── README.md
└── docs/
    └── Architecture.png

















