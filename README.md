 # 🏠 Booking Management System - Airbnb Clone

# 🏠 Airbnb Clone – Booking Management System

A full-featured clone of Airbnb focused on building a robust **Booking Management System**. This application simulates the core experience of property rental platforms with emphasis on both **frontend functionality** and a **powerful Django-based backend API**.

---

## 🚀 Objective

To develop a production-grade booking system that supports:
- Secure user authentication
- Property listing & management
- Booking lifecycle management
- Online payments
- User reviews

Built using Django, PostgreSQL, Docker, and modern web technologies, this project is a hands-on demonstration of software architecture, scalable design, and API-first thinking.

---

## 🏆 Project Goals

- **🔐 User Management** – Register, login, manage profile securely  
- **🏡 Property Listings** – List, edit, delete properties  
- **📅 Booking System** – Book and manage stays  
- **💳 Payment Processing** – Integrated with Stripe  
- **⭐ Review System** – Rate and review properties  
- **⚙️ Data Optimization** – Caching, indexing, async tasks

---

## 🧩 Features Overview

### 1. 📄 API Documentation
- OpenAPI Standard for REST
- Django REST Framework (DRF) for structured endpoints
- **GraphQL** support for flexible frontend queries

### 2. 🔐 User Authentication
- **Endpoints:**
  - `GET /users/`
  - `POST /users/`
  - `GET /users/{user_id}/`
  - `PUT /users/{user_id}/`
  - `DELETE /users/{user_id}/`
- JWT-based login system
- Profile updates

### 3. 🏘️ Property Management
- **Endpoints:**
  - `GET /properties/`
  - `POST /properties/`
  - `GET /properties/{property_id}/`
  - `PUT /properties/{property_id}/`
  - `DELETE /properties/{property_id}/`

### 4. 📆 Booking System
- **Endpoints:**
  - `GET /bookings/`
  - `POST /bookings/`
  - `GET /bookings/{booking_id}/`
  - `PUT /bookings/{booking_id}/`
  - `DELETE /bookings/{booking_id}/`

### 5. 💳 Payments
- **Endpoint:**
  - `POST /payments/`
- Stripe API integration

### 6. ⭐ Reviews
- **Endpoints:**
  - `GET /reviews/`
  - `POST /reviews/`
  - `GET /reviews/{review_id}/`
  - `PUT /reviews/{review_id}/`
  - `DELETE /reviews/{review_id}/`

### 7. ⚡ Performance
- PostgreSQL indexing
- Redis for caching
- Celery for background jobs (e.g., notifications)

---

## 🛠️ Tech Stack

**Frontend**
- React.js + Tailwind CSS
- Axios
- React Router

**Backend**
- Django + Django REST Framework
- GraphQL
- PostgreSQL
- Stripe API
- Celery + Redis
- Docker

**DevOps**
- Docker Compose
- CI/CD pipelines
- Nginx reverse proxy

---

## 📦 Setup & Installation

### 🔧 Backend Setup

```bash
cd backend
cp .env.example .env
docker-compose up --build
Note: You’ll need your Stripe keys, PostgreSQL URL, and JWT secret in the .env.

🌐 Frontend Setup

cd frontend
npm install
npm run dev
Frontend .env


VITE_API_URL=http://localhost:8000/api
VITE_STRIPE_PUBLIC_KEY=your_public_key

🧪 Testing

# Backend
docker-compose exec web python manage.py test

# Frontend
npm run test
🧠 Architecture

👥 Team Roles
Backend Developer: Django, DRF, GraphQL, Celery

Frontend Developer: React, API integration, UI/UX

DevOps Engineer: Docker, CI/CD, monitoring

QA Engineer: Manual + Automated testing

📚 Resources
System Design for Hotel Booking Apps

GraphQL vs REST

Docker for Python Projects

📃 License
This project is licensed under the MIT License.

💬 Connect
Joshua
🔗 https://www.linkedin.com/in/joshua-otieno
📧 joshuaonyango372@gmail.com
