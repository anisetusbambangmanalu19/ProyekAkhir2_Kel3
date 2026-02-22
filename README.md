📌 Project Overview
A mobile-based property booking application developed as a final project, designed to simplify the process of searching, booking, and managing kost and homestay properties.
This system supports multiple user roles (tenant, owner, admin, super admin) and integrates a RESTful API built with Laravel 11 as the backend and Flutter as the mobile frontend.
The application is designed with scalable architecture, secure authentication, and structured relational database design.

🚀 Key Features
👤 Multi-Role Authentication System
Secure login & registration
Password hashing
Role-based access control (Tenant, Owner, Admin, Super Admin)
Email verification (backend)

🔍 Property Search & Filtering
Search kost/homestay by location
Dynamic cascading dropdown (Province → City → District → Subdistrict)
Filter by price, facilities, and availability
Location-based data using stored procedures

🏠 Property Management (Owner)
Add, edit, delete property
Upload multiple property images
Manage rooms and pricing
Property facility management
Owner dashboard statistics

📅 Booking System
Online booking flow
Reservation management
Booking confirmation system
Status tracking (pending, approved, rejected)

❤️ Additional Features
Wishlist / Favorite properties
Property detail page with image gallery
Review & rating system
Notification & reminder system

🛠 Tech Stack
🔹 Frontend (Mobile)
Flutter
Dio (for API communication)
Clean UI design structure
State management implementation
🔹 Backend (API)
Laravel 11
RESTful API architecture
Stored Procedures (MySQL)
Authentication with hashed passwords
Role-Based Access Control (RBAC)
🔹 Database
MySQL (Railway)
Normalized relational database (1NF – 3NF)
Tables:
users
properties
rooms
property_images
property_facilities
bookings
reviews
provinces, cities, districts, subdistricts

🏗 System Architecture
The system is built using a separated architecture:
Flutter Mobile App
⬇
Laravel REST API
⬇
MySQL Database
Flutter communicates with Laravel using JSON-based REST API.
Laravel handles business logic and database operations.
Stored procedures are used for complex data operations and validation.
Dio handles authentication tokens and multipart image uploads.

🔐 Security Implementation
Password hashing
Token-based authentication
Role validation middleware
Backend validation for duplicate property prevention
Secure image upload handling

📊 Development Highlights
Designed full database schema from scratch
Implemented dynamic location filtering with AJAX & API
Built structured CRUD for property and booking
Integrated API into Flutter using Dio
Managed complex multi-role access system
Developed owner dashboard statistics

🎯 Project Goal
To build a scalable and production-ready property booking system that can be expanded into a real commercial platform.
