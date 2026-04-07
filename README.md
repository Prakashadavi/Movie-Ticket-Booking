# 🎬 Movie Ticket Booking System

A full-stack **Movie Ticket Booking Web Application** that allows users to browse movies, select seats, book tickets, and make payments seamlessly. Includes an **admin dashboard** for managing movies, shows, and bookings.

---

## 🚀 Features

### 👤 User Features
- 🔐 Authentication (Sign up / Login using Clerk)
- 🎥 Browse Movies & View Details
- ❤️ Add Movies to Favorites
- 🪑 Seat Selection System
- 🎟️ Book Movie Tickets
- 💳 Secure Payments using Stripe
- 📜 Booking History & User Dashboard
- 📧 Email Notifications (Booking Confirmation & Reminders)

---

### 🛠️ Admin Features
- 📊 Admin Dashboard
- 🎬 Add / Update / Delete Movies (CRUD)
- 🕒 Manage Show Timings
- 🎟️ View & Manage Bookings
- 📈 Real-time Data Integration

---

### ⚙️ Backend Features
- RESTful APIs (Node.js + Express)
- Database Integration (MongoDB)
- Seat Locking & Expiration Logic
- Payment Verification via Stripe Webhooks
- Secure Authentication Handling

---

## 🧑‍💻 Tech Stack

### Frontend
- React.js
- Tailwind CSS
- React Router
- Clerk Authentication

### Backend
- Node.js
- Express.js
- MongoDB

### Payment
- Stripe API
- Stripe Webhooks

### Deployment
- Docker (optional)
- Nginx (optional)
- AWS / Vercel / Render

---

## 📁 Project Structure
project-root/
│
├── frontend/
│ ├── src/
│ ├── pages/
│ ├── components/
│ └── services/
│
├── backend/
│ ├── models/
│ ├── controllers/
│ ├── routes/
│ └── server.js
│
├── nginx/ (optional)
├── docker-compose.yml (optional)
└── README.md


---

## ⚡ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/movie-booking-app.git
cd movie-booking-app

Create .env file:
PORT=5000
MONGO_URI=your_mongodb_url
STRIPE_SECRET_KEY=your_stripe_secret
WEBHOOK_SECRET=your_webhook_secret