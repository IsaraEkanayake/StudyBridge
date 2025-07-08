# 🧳 Study Bridge – Student Migration System for Foreign Universities

<div align="center">

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![MongoDB](https://img.shields.io/badge/MongoDB-4.4-green)](https://www.mongodb.com/)
  [![React](https://img.shields.io/badge/React-18.2-blue)](https://reactjs.org/)
  [![Node.js](https://img.shields.io/badge/Node.js-16.x-green)](https://nodejs.org/)
</div>


## 📋 Overview

Study Bridge is a comprehensive student migration management system designed to simplify and automate the process of applying and transitioning to foreign universities. Built using the MERN stack, the platform supports multiple stakeholders, including students, universities, and administrative officers.

This system streamlines end-to-end academic and migration processes by integrating essential modules such as visa processing, student management, academic scheduling, financial tracking, and university administration.

# 🌉 Study Bridge – Student Migration System

**Tech Stack**: MERN (MongoDB, Express.js, React.js, Node.js)

Study Bridge is a full-stack web application built to streamline the end-to-end student migration process for foreign universities. This platform connects students, universities, and visa officers into one centralized system for efficient academic and migration workflow management.

---

## ✨ Features

### 🔐 User Authentication & Authorization
- Secure student and admin registration & login
- Role-based access (Student, University, Visa Officer, Admin)

### 🎓 Student Management
- Student profile creation and updates
- Document uploads (passport, academic records, etc.)
- University application tracking

### 🏛️ University Management
- University registration and dashboard
- Course & intake creation
- Offer letter generation and student enrollment

### 🛂 Visa Management
- E-Visa application and processing
- Real-time status tracking and notifications
- Appointment scheduling and report download

### 🧾 Financial Management
- Tuition and visa fee tracking
- Multiple payment support and receipt generation
- Scholarship management

### 📅 Exam & Assessment Module
- Exam schedule creation (IELTS, TOEFL, etc.)
- Test result uploads and verification

### 📬 Notification System
- Visa status update notifications

### 📊 Dashboard & Analytics
- Application trends, visa approvals, and user activity
- Exportable reports and visual charts

---

## 💻 Tech Stack

| Layer         | Technology                  |
|---------------|------------------------------|
| Frontend      | React.js, Bootstrap, Material UI |
| Backend       | Node.js, Express.js         |
| Database      | MongoDB                     |
| Authentication| bcrypt                      |
| APIs          | RESTful API                 |
| Version Control | Git, GitHub               |

---

## 🚀 Getting Started

### Prerequisites
- Node.js & npm
- MongoDB (local or Atlas)

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/study-bridge.git
cd study-bridge

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

# Start backend
cd ../backend
npm run dev

# Start frontend
cd ../frontend
npm start


## 🚀 Getting Started

### Prerequisites
- npm (v8.x or higher)
- MongoDB (v4.4 or higher)

### Installation


## 🛠️ Development

### Project Structure
```
StudyBridge /
├── frontend/                 # React frontend application
├── backend/                  #springboot backend
└── README.md                 # Project documentation
```

### Environment Variables

Each service requires specific environment variables. Create `.env` files in each service directory with the following variables:

```env
# MongoDB Connection
MONGODB_URI=mongodb://localhost:27017/StudyBridge


# Service Ports
PORT=8080 # Adjust port number for each service
```



## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



## 🙏 Acknowledgments

- [MongoDB](https://www.mongodb.com/)



