# Node.js Course API 🎓

A RESTful API built with Node.js and Express.js that manages courses, authors, and users.  
Includes authentication, authorization, and MongoDB integration.

## 🛠 Tech Stack
- Node.js
- Express.js
- MongoDB (via Mongoose)
- JWT (Authentication)
- Bcrypt (Password Hashing)
- dotenv (Config)

## 📦 Features
- JWT-based user authentication (Login/Register)
- Role-based access control (admin, user)
- CRUD operations for:
  - Courses
  - Authors
- Middleware for:
  - Auth
  - Authorization
- MongoDB integration with schema validation


## ▶️ Getting Started

### Prerequisites
- Node.js (v14+)
- MongoDB (local or MongoDB Atlas)

### Installation
```bash
git clone https://github.com/samerben/API-NodeJS.git
npm install
npm run dev
