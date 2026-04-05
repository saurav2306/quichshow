# 🎬 QuickShow – Movie Ticket Booking Website     
🌐[Click Here to View Website](https://quichshow-ja9c.vercel.app/)

A Full Stack Movie Ticket Booking Web Application built using the MERN Stack. Users can explore movies, watch trailers, and book tickets with real-time seat selection. An admin dashboard is also included to manage movies and bookings.

---

## 🚀 Features

### 👤 User Features
- 🔐 Authentication using Clerk (Email, Social)
- 👥 Multi-session login (multiple profiles)
- 🎬 Browse movies & watch trailers
- 🪑 Real-time seat selection
- 🎟️ Book tickets easily
- 💳 Secure payment integration
- 📩 Booking confirmation & reminder emails

---

### 🛠️ Admin Features
- ➕ Add new movies
- 🎬 Manage shows
- 📊 View all bookings
- 📢 Notify users when new movies are added

---

### ⚙️ Background Jobs
- 📧 Send booking confirmation emails
- ⏰ Send reminder emails before showtime
- 📢 Notify users on new movie release

---

### ⏱️ Smart Seat Lock System
- Seats are reserved for **10 minutes** during payment
- If payment fails → seats remain locked temporarily
- Auto-release seats after 10 minutes if unpaid

---

## 🏗️ Tech Stack

### Frontend
- React
- Tailwind CSS
- Vite

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Authentication
- Clerk

### Background Jobs
- Inngest

---

## 📂 Project Structure
- client/ # Frontend (React + Vite)
- server/ # Backend (Node + Express)
- README.md

---
## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://github.com/apps/vercel) from the creators of Next.js.
