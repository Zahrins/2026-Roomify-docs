# Roomify System Documentation

This repository contains the complete documentation for the Roomify system.

Roomify is a room reservation system built using a modern client-server architecture with role-based access control.

---

## 📌 System Overview

Roomify consists of:

- Frontend (React + Vite + Tailwind CSS)
- Backend (ASP.NET Core Web API)
- PostgreSQL Database
- JWT Authentication

The system allows users to book rooms and admins to manage buildings, rooms, and booking approvals.

---

## 🏗 System Architecture

Client-Server Architecture:

Frontend (React)
        ↓ HTTP (Fetch API)
Backend (ASP.NET Core)
        ↓
PostgreSQL Database

Authentication is handled using JWT Bearer Tokens.

---

## 🔗 Related Repositories

- Frontend: https://github.com/Zahrins/2026-Roomify-frontend
- Backend: https://github.com/Zahrins/2026-Roomify-Backend
- Infrastructure: https://github.com/Zahrins/2026-Roomify-infrastructure

---

## 🚀 Core Features (System Level)

- JWT Authentication (Admin & User roles)
- Room booking management
- Booking approval workflow
- Booking history tracking
- Pagination & filtering
- Role-based access control

---

## 📡 API Overview

Base URL:
https://localhost:7252/api

Modules:
- User
- Building
- Booking
- Room
- BookingStatusHistory

Swagger:
https://localhost:7252/swagger

---

## 🔄 Git Workflow

Branch Strategy:

- main → stable production branch
- develop → integration branch
- feature/* → new features

Workflow:

1. Create feature branch
2. Implement feature
3. Merge into develop
4. Release version using tag (v1.0.0)

---

## 🛠 Full System Setup Guide

1. Run Backend
   - Configure appsettings
   - Run migrations
   - Start API

2. Configure Frontend
   - Copy .env.example
   - Set VITE_API_URL

3. Run Frontend
   npm run dev

---

## 📈 Future Improvements

- Add room details (location, capacity, facilities)
- Room detail page

---

## Author

Zahrin Savana Khadijah  
Roomify Project Documentation
