# 🚀 Task Manager (MERN Stack)

A full-stack **Task Management Web Application** built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js).

---

## 🌐 Live Demo

* **Frontend (Netlify): [Live Demo](https://luxury-paletas-eb3401.netlify.app)
* **Backend API (Render):** [Live Demo](https://task-manager-b-2.onrender.com)
---

## 📌 Features

### 👤 Authentication

* User Signup & Login
* JWT Authentication
* Secure HTTP-only Cookies
* Role-based access (Admin/User)
* Protected Routes

### 📋 Task Management

* Create Tasks
* Update Tasks
* Delete Tasks
* Task Status Tracking
* Dashboard Analytics

### 👨‍💼 Admin Features

* Admin-only routes
* Team member management
* Task monitoring

### 🎨 UI/UX

* Modern Premium Dashboard UI
* Responsive Design
* Tailwind CSS styling
* Charts & analytics visualization

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Redux Toolkit
* Tailwind CSS
* Axios
* React Router

### Backend

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* JWT Authentication
* Cookie Parser
* Multer (Image Upload)

### Deployment

* Frontend → Netlify
* Backend → Render
* Database → MongoDB Atlas

---

## 📂 Project Structure

```
Task-Manager
│
├── frontend        # React Application
│
├── backend         # Express API
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   └── index.js
│
└── README.md
```

---

## ⚙️ Environment Variables

Create `.env` file inside **backend** folder:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
FRONT_END_URL=http://localhost:5173
ADMIN_JOIN_CODE=your_admin_code
```

⚠️ Never commit `.env` file.

---



### 2️⃣ Backend Setup

```
cd backend
npm install
npm run dev
```

Server runs at:

```
http://localhost:3000
```

---

### 3️⃣ Frontend Setup

```
cd frontend
npm install
npm run dev
```

Frontend runs at:

```
http://localhost:5173
```

---

## 🔐 Authentication Flow

1. User logs in
2. Backend generates JWT token
3. Token stored in HTTP-only cookie
4. Cookie sent automatically with requests
5. Middleware verifies token for protected routes

---

## ☁️ Deployment Guide

### Backend (Render)

* Connected GitHub repository
* Added environment variables
* Auto deploy enabled

### Frontend (Netlify)

* Build command: `npm run build`
* Publish directory: `dist`
* Connected to live backend API

---

## 🔒 Security Features

* Password hashing using bcrypt
* HTTP-only cookies
* Secure cross-origin authentication
* Role-based authorization middleware
* Environment variable protection

---

## 📊 API Routes

| Method | Endpoint           | Description      |
| ------ | ------------------ | ---------------- |
| POST   | /api/auth/sign-up  | Register user    |
| POST   | /api/auth/sign-in  | Login user       |
| POST   | /api/auth/sign-out | Logout user      |
| GET    | /api/users/profile | Get user profile |
| GET    | /api/tasks         | Fetch tasks      |
| POST   | /api/tasks         | Create task      |

---

## 🧠 Learning Outcomes

* Full MERN stack development
* Authentication & authorization
* Production deployment
* REST API design
* MongoDB Atlas integration
* CORS & cookie handling
* Real-world debugging

---

## 👨‍💻 Author

**Himanshu Chaudhary**
B.Tech Computer Science
Frontend & MERN Stack Developer

---

## ⭐ Future Improvements

* Dark Mode
* Real-time notifications
* Team collaboration chat
* Email verification
* Task reminders

---


