# 🚤 Boat Booking System – Tankua

A smart and simple boat booking platform designed to improve tourism, elevate customer experience, and empower boat owners in Bahir Dar. Built using **Next.js** for the frontend and **Node.js + Express** for the backend, the system allows customers to easily explore, reserve, and enjoy boat services with transparency and convenience.

---

## 🎯 Purpose

This platform is built to:
- Modernize the local boat rental experience
- Provide digital access for tourists and residents
- Empower boat owners with a professional admin panel
- Support the local economy by streamlining operations

---

## 🧱 Tech Stack

| Layer       | Technology         |
|-------------|--------------------|
| Frontend    | Next.js + Tailwind |
| Backend     | Node.js + Express  |
| Database    | MySQL              |
| Auth        | JWT (HttpOnly)     |
| Charts      | Recharts           |
| Deployment  | Vercel + Railway   |

---

## ⚙️ Core Features

### 🚀 For Customers
- Browse available boats with filters (price, size, availability)
- View boat images and details
- Select trip time and duration
- Instant or scheduled bookings
- Ratings and reviews

### 🧑‍💼 For Boat Owners
- Dashboard to manage boats, bookings, earnings
- Set pricing and availability
- Receive customer booking alerts
- Track earnings with charts
- Withdraw funds to bank or wallet

### 👨‍💻 For Admin
- Approve/verify boat owners
- Manage users and listings
- Track total system earnings
- Handle disputes or issues
- Monitor performance and system activity

---

## 💰 Business Model

- The platform **takes 10% commission** from every completed booking
- VAT and payment processing fees are also deducted before payout
- Boat owners receive **net earnings** after these deductions

### 📊 Sample Booking Breakdown

| Description               | Amount (ETB) |
|---------------------------|--------------|
| Total Customer Payment    | 1000         |
| Platform Commission (10%) | 100          |
| VAT (e.g. 15%)            | 150          |
| **Payout to Owner**       | **750**      |

---

## 🖼️ Business Model Diagram (Text-Based)

+------------------+ | Customer | | (Books a Boat) | +------------------+ | v +--------------------------+ | Booking System | | - Takes 10% Commission | | - Adds VAT & Processing | +--------------------------+ | v +------------------+ +------------------+ | Platform Earnings|<------| Boat Owner | | (Commission & VAT)| | Receives Net Pay| +------------------+ +------------------+


---

## 🗃️ Database Tables (MySQL)

| Table            | Description                  |
|------------------|------------------------------|
| `users`          | User accounts                |
| `boats`          | Boat listings                |
| `bookings`       | Booking transactions         |
| `reviews`        | Customer feedback            |
| `payments`       | Payment records              |
| `earnings`       | Commission and payout logs   |

---

## 🔐 Security Features

- ✅ JWT Auth (HttpOnly cookies)
- ✅ Role-based access (admin, owner, user)
- ✅ XSS and SQL Injection protection
- ✅ Bcrypt password hashing
- ✅ Helmet for secure headers
- ✅ CORS configured properly
- ✅ Rate limiting for login and booking

---

## 🌍 Deployment Plan

| Component | Platform         |
|-----------|------------------|
| Frontend  | Vercel           |
| Backend   | Railway / VPS    |
| Database  | PlanetScale / MySQL |
| Domain    | y_city.com       |

---

## 📈 Future Improvements

- SMS/email notifications for booking confirmation
- Mobile app integration
- Ethiopian languages support (Amharic, Afaan Oromo)
- Multi-day package tours
- Seasonal discount codes

---

## 🧠 Contact

For questions or partnership opportunities, reach out via:
- 📧 Email: `nahomkeneni4@gmail.com`

---

> “We’re not just renting boats — we’re creating memorable journeys across Bahir Dar’s waters.”

