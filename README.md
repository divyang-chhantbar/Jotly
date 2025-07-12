# 📝 Jotly — Full-Stack Blogging Platform

Jotly is a full-stack blogging application built with the MERN stack (MongoDB, Express, React, Node.js). It allows users to sign up, log in, and manage their blogs with features like filtering, searching, pagination, and a clean dashboard interface.

---

## 🚀 Features

### ✅ Authentication
- User Signup & Signin with JWT-based authentication
- Secure password hashing using bcrypt

### 📝 Blog Management
- Create, edit, and delete blog posts
- View blogs with pagination and filtering (e.g., by theme)
- Blog search functionality
- Responsive dashboard UI

### 📊 Tech Stack

| Layer       | Tech                          |
|-------------|-------------------------------|
| Frontend    | React.js + Vite + Tailwind CSS |
| Backend     | Node.js + Express.js          |
| Database    | MongoDB (with Mongoose ORM)   |
| Auth        | JWT (JSON Web Tokens)         |
| Styling     | Tailwind CSS + ShadCN UI      |

---

## 🧱 Folder Structure

jotly/
├── backend/         # Express.js API with MongoDB
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── ...
├── frontend/        # React + Vite based UI
│   ├── pages/
│   ├── components/
│   └── ...
├── .gitignore
└── README.md

---

## 🧑‍💻 Local Development

### Prerequisites
- Node.js >= 18
- MongoDB (local or Atlas)

### 1. Clone the repository

```bash
git clone https://github.com/divyang-chhantbar/Jotly.git
cd Jotly
