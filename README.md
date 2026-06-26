

# 🚀 LearnNexus

**AI-Powered Learning & Community Platform**

---

## 📌 Overview

LearnNexus is an **AI-powered educational platform** designed to help students **learn smarter and collaborate effectively**. It combines structured learning, AI tutoring, and a community-driven Q&A system in one unified platform.

The platform enables users to upload notes, explore topics, interact with an AI tutor, and engage in discussions — all while receiving real-time feedback and intelligent assistance.

---

## ✨ Features

### 📚 Learning System

* Upload and view notes (PDF/Image)
* Explore subjects and structured content
* Personalized learning experience

### 🤖 AI Tutor

* Generates learning roadmaps
* Provides explanations and quizzes
* Real-time AI progress updates using sockets

### 💬 Nexus Board (Community)

* Create posts and ask questions
* Comment and reply in threads
* Upvote and bookmark posts
* Mark answers as accepted

### 🕵️ Anonymous Posting

* Users can post anonymously
* Identity hidden from other users
* Optional feature with credit cost

### 🧠 Smart AI Features

* AI-based tag normalization
* Toxic content detection & filtering
* Intelligent content processing

### ⚡ Credit System

* Earn and spend credits
* Used for features like anonymous posting

### 🔒 Authentication & Roles

* Secure login system
* Role-based access (User, Admin)

---

## 🏗️ Tech Stack

### Frontend

* React (Hooks, Component-based architecture)
* React Router (Routing)
* Tailwind CSS (Styling)
* Framer Motion (Animations)
* Socket.IO Client (Real-time updates)

### Backend

* REST APIs for data handling
* Authentication & authorization
* AI processing integration
* Real-time communication (Socket.IO)

---

## 🔄 System Architecture

```text
Frontend (React)
        ↓
      API
        ↓
   Backend Server
        ↓
     Database
```

* Frontend communicates with backend using APIs
* Backend handles business logic and database operations
* Socket.IO enables real-time updates (AI progress, notifications)

---

## 🔌 Key API Usage

* `GET` → Fetch data (posts, comments)
* `POST` → Create data (posts, comments)
* `PATCH/PUT` → Update data (likes, bookmarks)
* `DELETE` → Remove data

---

## ⚡ Real-Time Features

* AI progress updates (e.g., roadmap generation)
* Live notifications using Socket.IO
* Instant UI feedback without refreshing

---

## 🔐 Security & Moderation

* Role-based access control
* Protected routes for authenticated users
* Toxicity detection system blocks harmful content
* Anonymous posting handled securely at backend

---

## 📁 Project Structure (Frontend)

```text
src/
 ├── components/
 │    ├── common/
 │    ├── ui/
 │    ├── community/
 │
 ├── pages/
 ├── context/
 ├── services/   (API calls)
 ├── layout/
 └── App.jsx
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/learnnexus.git
cd learnnexus
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the frontend

```bash
npm run dev
```

### 4. Setup environment variables

Create `.env` file:

```env
VITE_API_BASE_URL=http://localhost:5000
VITE_SOCKET_URL=http://localhost:5000
```

---

## 🎯 Key Highlights

* Combines **AI + Community Learning**
* Real-time system using **Socket.IO**
* Clean, reusable React architecture
* Focus on **user experience and scalability**

---

## 📈 Future Improvements

* Personalized AI recommendations
* Mobile app version
* Advanced analytics dashboard
* Gamification system

---

## 📄 License

This project is for educational purposes.

---
