
<div align="center">

# 🚀 Talent-IQ
### Real-Time Coding Interview Platform

A full-stack real-time coding interview platform with live video calls, collaborative coding, real-time chat, and automated code evaluation — all in one system.

</div>

---

## 🎬 Platform Demo

<!-- Replace with your uploaded GitHub video URL -->

[https://github.com/user-attachments/assets/YOUR-VIDEO-ID](https://github.com/user-attachments/assets/61d1df09-3a8a-4a2d-a7c7-a100a0c45af1)

---

## 🌟 Features

- 🧑‍💻 VSCode-powered online code editor (Monaco)
- 🎥 1-on-1 Video Interview Calls (Stream Video)
- 💬 Real-time Chat Messaging
- 🔐 Authentication & User Management (Clerk)
- ⚙️ Secure Code Execution with Test Case Evaluation
- 🎯 Auto Feedback (Pass / Fail)
- 🔒 Room Locking (Only 2 Participants Allowed)
- 🧭 Dashboard with Interview Stats
- 🧩 Practice Mode (Solo Coding)
- 🔄 Background Jobs & Webhooks (Inngest)
- ⚡ Fast Data Fetching (TanStack Query)
- 🚀 Production Deployment Ready

---

## 🏗 Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- TanStack Query
- Monaco Editor

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)

### Real-Time & Infrastructure
- Stream (Video + Chat)
- Clerk (Authentication)
- Inngest (Background Jobs)

---

## 🧠 System Architecture

```text
             Client (React + Vite)
                     |
                     v
             REST API (Express.js)
                     |
                     v
              MongoDB Database
                     |
                     v
          Real-Time Layer (Stream)
                     |
                     v
           Background Jobs (Inngest)
```

---

## 🔥 Core Functionalities

### 🎥 Real-Time Video Interviews
- WebRTC-powered sessions
- Mic / Camera toggle
- Screen sharing
- Recording support

### 💬 Real-Time Chat
- Instant messaging
- WebSocket-based synchronization
- Secure channel access

### 🧑‍💻 Collaborative Code Editor
- Syntax highlighting
- Multi-language support
- Real-time coding environment

### ⚙️ Secure Code Execution
- Code runs in an isolated environment
- Automatic test case validation
- Instant pass/fail feedback

### 🔐 Authentication & Sync
- Clerk-based authentication
- Webhook-driven user synchronization
- Automatic Stream user provisioning

### 🔒 Room Management
- Only 2 participants allowed
- Session locking
- Role-based access control

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/talent-iq.git
cd talent-iq
```

### 2️⃣ Backend Setup

```bash
cd backend
npm install
npm run dev
```

Create a `.env` file inside the backend directory:

```env
PORT=5000
MONGO_URI=your_mongodb_uri
CLERK_SECRET_KEY=your_clerk_secret
STREAM_API_KEY=your_stream_key
STREAM_SECRET=your_stream_secret
INNGEST_SIGNING_KEY=your_inngest_key
```

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 📦 Deployment

| Service | Platform |
|---|---|
| Frontend | Render |
| Backend | Render |
| Database | MongoDB Atlas |
| Video & Chat | Stream |
| Authentication | Clerk |
| Background Jobs | Inngest |

---

## 👨‍💻 Author

**Akshay Anand**

- GitHub: [Akshay4754](https://github.com/Akshay4754)

---

<div align="center">

### ⭐ If you like this project, consider giving it a star!

Built with ❤️ by Akshay Anand

</div>
