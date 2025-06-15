# 💬 Talkon

**Talkon** is a full-stack real-time chat application built with the **MERN stack** and **Socket.IO**. It features secure authentication, image sharing, user search, and an elegant UI designed for both desktop and mobile.

---

## 🚀 Features

- 🔐 JWT-based user authentication  
- ⚡ Real-time messaging via Socket.IO  
- 🖼️ Image sharing in chats  
- 🧑‍💼 User profiles with bios  
- 🔎 Search functionality  
- 📁 Clean, component-based architecture  
- 🧑‍💻 Fully responsive design  

---

## 🛠️ Tech Stack

### 🔹 Frontend
- React.js  
- Tailwind CSS  
- React Router  
- React Hot Toast  

### 🔸 Backend
- Node.js  
- Express.js  
- MongoDB (Mongoose)  

### 🔁 Real-Time
- Socket.IO  

### ☁️ Deployment
- Vercel (Frontend)  
- Render / Cyclic / Railway / Others (Backend)

---

## ⚙️ Getting Started

### 🖥️ Setup: Client

```bash
cd client
npm install
npm run dev
⚙️ Setup: Server
bash
Copy
Edit
cd server
npm install
npm run start
🔐 Environment Variables
Create a .env file in both the client and server folders:

✅ server/.env
env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
✅ client/.env
env
Copy
Edit
VITE_BACKEND_URL=http://localhost:5000
⚡ Socket.IO Integration
This project uses WebSockets (via Socket.IO) to handle real-time messaging between users.

📡 Client Emits / Listens
sendMessage → Sent when a user sends a message

receiveMessage → Listens for new incoming messages

newUser → Triggered when a user connects

🖥️ Server Responsibilities
Track online users

Broadcast messages in real-time

Handle user connect/disconnect events

👨‍💻 Author
@palakverma25
