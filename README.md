# 🚖 RideSync – Real-Time Ride-Hailing Platform

RideSync is a full-stack ride-hailing application inspired by modern transportation platforms. Built using the MERN stack, the project provides a seamless experience for both passengers and drivers through real-time ride management, location services, and secure authentication.

## 📌 Overview

RideSync enables users to book rides, track ride status in real time, and connect with nearby drivers. The platform supports separate workflows for passengers and captains (drivers), ensuring a smooth and scalable ride-booking experience.

This project demonstrates full-stack development concepts, including authentication, RESTful APIs, real-time communication, state management, and third-party API integration.

---

## ✨ Key Features

### 👤 User & Captain Authentication

* Secure registration and login system
* JWT-based authentication and authorization
* Protected routes using custom middleware
* Password encryption with bcrypt

### 🚗 Ride Management

* Create and request rides
* Dynamic fare calculation
* Ride lifecycle management
* Ride acceptance and completion workflow

### 📍 Google Maps Integration

* Location search and suggestions
* Geolocation support
* Distance and travel time calculation
* Route-based fare estimation

### ⚡ Real-Time Communication

* Socket.io integration for instant updates
* Real-time ride requests
* Live ride status tracking
* Captain ride acceptance notifications

### 🎨 Modern User Interface

* Mobile-first responsive design
* Clean and intuitive user experience
* Interactive ride confirmation panels
* Location search and ride booking interface

---

## 🏗️ System Architecture

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Socket.io

### Frontend

* React.js
* Vite
* Tailwind CSS
* React Context API
* Remix Icons

### External Services

* Google Maps Geolocation API
* Google Maps Directions API

---

## 📂 Project Structure

```bash
RideSync/
│
├── Backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── services/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── hooks/
│   │   └── services/
│   └── vite.config.js
│
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

* Node.js
* MongoDB
* Google Maps API Key
* npm

---

### Installation

#### Clone the Repository

```bash
git clone https://github.com/Kartik247-coder/RideSync-Ride-Hailing-Backend.git
cd RideSync-Ride-Hailing-Backend
```

### Backend Setup

```bash
cd Backend
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_MAPS_API=your_google_maps_api_key
```

Start the backend server:

```bash
npm start
```

---

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

The application will be available at:

```text
http://localhost:5173
```

---

## 🔄 Application Workflow

1. User registers or logs in.
2. User selects pickup and destination locations.
3. Fare is calculated using Google Maps APIs.
4. Ride request is broadcast to nearby captains.
5. Captain accepts the ride.
6. Real-time ride updates are shared via Socket.io.
7. Ride is completed and stored in the database.

---

## 🔒 Security Features

* JWT Authentication
* Password Hashing with Bcrypt
* Protected API Routes
* Role-Based Access Control
* Secure Environment Variable Management

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience with:

* Full-Stack MERN Development
* REST API Design
* Real-Time Communication using Socket.io
* Authentication & Authorization
* Google Maps API Integration
* MongoDB Data Modeling
* React State Management
* Scalable Application Architecture

---

## 🌟 Future Enhancements

* Online Payment Integration
* Ride History Dashboard
* Driver Ratings & Reviews
* Admin Panel
* Push Notifications
* Ride Scheduling
* Surge Pricing System

---

## 👨‍💻 Author

**Kartik Bobde**

* Java | JavaScript | MERN Stack
* Backend Development
* AI/ML Enthusiast
* Data Structures & Algorithms

If you found this project useful, consider giving it a ⭐ on GitHub.
