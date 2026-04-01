# SkillBridge 🚀  
### Online Marketplace for Freelancers (Fiverr-like Platform)

SkillBridge is a full-stack MERN web application that connects **clients** and **freelancers** on a single platform.  
It allows freelancers to create and manage service gigs, clients to browse and purchase services, and both to communicate via real-time chat.  
An **admin panel** is included for platform monitoring and moderation.

This project is built as an **academic + real-world project**, demonstrating role-based systems, CRUD operations, dashboards, and real-time features.

---

## 📌 Key Features

### 🔐 Authentication & Roles
- JWT-based authentication
- Role-based access:
  - Client
  - Freelancer
  - Admin
- Protected routes for each role
---

### 👜 Freelancer Features
- Create, edit, and delete gigs
- View all own gigs
- Receive orders from clients
- Track:
  - Active orders
  - Gross earnings
  - Net earnings
  - Platform fee
- Real-time chat with clients

---

### 👤 Client Features
- Browse all available gigs
- View gig details
- Place orders (payment simulated)
- Track orders:
  - Pending
  - Active
  - Completed
- View total spending
- Real-time chat with freelancers

---

### 🛠 Admin Features
- Admin dashboard with platform statistics
- View all users with roles
- Ban / unban users
- View and delete gigs
- View all reviews
- Monitor orders and revenue trends

---

### 💬 Real-Time Chat
- One-to-one messaging between client and freelancer
- Built using Socket.io
- Messages stored in database

---

### 💳 Payments
- Payment flow implemented using **dummy logic**
- Stripe payment gateway planned as future scope

---

## 🛠 Tech Stack

### Frontend
- React.js (Vite)
- Tailwind CSS
- React Router
- Fetch API

### Backend
- Node.js
- Express.js
- MongoDB & Mongoose
- JWT Authentication
- Socket.io

---

## 📁 Project Structure
skillbridge/
├── client/
│ ├── public/
│ ├── src/
│ ├── package.json
│ └── vite.config.js
│
├── server/
│ ├── config/
│ ├── controllers/
│ ├── middleware/
│ ├── models/
│ ├── routes/
│ ├── server.js
│ └── package.json
│
└── README.md
