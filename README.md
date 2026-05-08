# Music_Application_Backend
# Music Streaming Backend System

A scalable backend system for a Spotify-like music streaming platform built using **Node.js**, **Express.js**, and **MongoDB**. The application supports secure authentication, role-based access control, media uploads, album/song management, and dynamic music retrieval.

---

# Features

* JWT-based Authentication
* Password Hashing for Secure User Management
* Role-Based Access Control (Artist & User)
* Song Upload & Management
* Album Creation & Management
* MongoDB Database Integration
* Image & Media Upload using Multer and ImageKit
* RESTful API Architecture
* Modular MVC-Inspired Backend Structure
* Middleware-Based Authorization

---

# Tech Stack

## Backend

* Node.js
* Express.js

## Database

* MongoDB
* Mongoose

## Authentication & Security

* JWT (JSON Web Tokens)
* bcrypt

## File Handling

* Multer
* ImageKit

---

# Roles Implemented

## Artist
Artists are allowed to:
* Upload songs
* Create albums
* Manage music content

## User
Users can:
* View songs and albums
* Access music content

Role-based access control ensures that only artists can upload and manage music.

---

# Project Structure

```bash
src/
│
├── controllers/       # Business logic
├── routes/            # API routes
├── models/            # MongoDB schemas
├── middlewares/       # Authentication middleware
├── services/          # External services (ImageKit)
├── db/                # Database connection
│
├── app.js             # Express app configuration
├── server.js          # Server entry point
```

---

# API Functionalities

## Authentication
* User Signup
* User Login
* JWT Token Generation

## Music Management
* Upload Music
* Fetch Songs
* Manage Songs

## Album Management
* Create Albums
* Retrieve Albums

---

# Architecture

The project follows a modular MVC-inspired architecture:

* **Models** handle database schemas and data structure
* **Controllers** manage application logic
* **Routes** define API endpoints
* **Middleware** handles authentication and authorization
* **Services** manage external integrations like ImageKit

This structure improves maintainability, scalability, and separation of concerns.

---

# Security Features

* Passwords are securely hashed using bcrypt
* JWT authentication protects private routes
* Role-based middleware restricts unauthorized access

---

# Learning Outcomes
Through this project, I gained hands-on experience in:

* Backend development using Node.js and Express
* Designing RESTful APIs
* Authentication and authorization
* Database schema design with MongoDB
* File upload handling using Multer
* Cloud media management with ImageKit
* Structuring scalable backend applications

---

# Future Improvements

* Music Streaming Support
* Playlist Functionality
* Search & Filtering
* Like/Save Songs
* Admin Dashboard
* Docker Deployment
* Cloud Hosting

---

# Author

Sarvam Taneja

GitHub: [https://github.com/Sarvamtaneja](https://github.com/Sarvamtaneja)
