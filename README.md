# 🏥 Dr. Maggessy Physiotherapy

<p align="center">
  <img src="https://img.shields.io/badge/Status-In%20Progress-yellow" />
  <img src="https://img.shields.io/badge/Focus-Full%20Stack-blue" />

  <a href="https://github.com/ThayronyVonHeld/Clinica-Clara-Fisioterapeuta/blob/main/README-PT.md">
    <img src="https://img.shields.io/badge/Languages-EN%20%7C%20PT--BR-green">
  </a>

</p>

---

A complete web system for managing appointments in a physiotherapy clinic.

The project allows user registration, JWT authentication login, appointment scheduling, and an administrative dashboard for the receptionist.

---

# 🚀 Deployment

* 🌐 Frontend: [https://clinica-clara-fisioterapeuta.vercel.app/](https://clinica-clara-fisioterapeuta.vercel.app/)
* ⚙️ Backend: [https://clinica-clara-fisioterapeuta.onrender.com](https://clinica-clara-fisioterapeuta.onrender.com)

---

# 🧠 Features

## 👤 User

* Account registration
* Login with JWT authentication
* Appointment scheduling
* View appointments
* Cancel appointments

## 🧑‍💼 Receptionist

* View all appointments
* Access patient data

---

# 🛠️ Technologies Used

## Backend

* Node.js
* Express
* MongoDB Atlas
* Mongoose
* JWT (JSON Web Token)
* Bcrypt

## Frontend

* Vue.js 3
* Axios
* Vue Toastification
* Modern responsive CSS design

## Deployment

* Vercel (Frontend)
* Render (Backend)

---

# 🔐 Authentication

The system uses JWT-based authentication:

* Token generated at login
* Stored in the frontend
* Sent in request headers:

```
Authorization: Bearer TOKEN
```

* Middleware protects private routes

---

# 📦 Project Structure

```
📁 backend
├── config
├── models
├── routes
├── middlewares
├── services
└── server.js

📁 frontend
├── components
├── views
├── services
└── main.js
```

---

# ⚙️ How to Run Locally

## 🔧 Backend

```bash
cd backend
npm install
npm run dev
```

## 🔧 Frontend

```bash
cd frontend
npm install
npm run dev
```

---

# 🌎 Environment Variables

Create a `.env` file in the backend:

```env
PORT=3000
MONGO_URI=your_mongo_uri
JWT_SECRET=your_secret
```

---

# 🔌 Integrations

* Weather API (OpenWeather)
* ZIP Code API

---

# 📌 Future Improvements

* Notification system
* Analytics dashboard with charts
* Improved mobile responsiveness
* UI/UX redesign upgrade

---

# 👨‍💻 Author

**Thayrony Von Held**

* Information Systems student
* Full Stack Developer in training

---

# 📢 Notes

This project was developed for practical learning purposes, simulating a real-world clinic management system.

---
