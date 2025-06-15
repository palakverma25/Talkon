# Talkon 💬

**Talkon** is a full-stack real-time chat application powered by the **MERN stack** and enhanced with **Socket.IO** for instant, bidirectional messaging. It offers seamless user experiences with secure authentication, a responsive interface, and dynamic chat features.

---

## 🚀 Features

- 🔐 JWT-based User Authentication  
- ⚡ Real-time Chat using Socket.IO  
- 🖼️ Image Sharing in Messages  
- 🧑‍💼 Profile Pages with User Bio  
- 📁 Clean, Component-Based Architecture  
- 🔎 User Search Functionality  
- 🧑‍💻 Fully Responsive UI (Mobile/Desktop)  

---

## 🛠️ Tech Stack

### 🧩 Frontend:
- React.js  
- Tailwind CSS  
- React Router  
- React Hot Toast (notifications)  

### 🔧 Backend:
- Node.js  
- Express.js  
- MongoDB (with Mongoose)  

### 🔁 Real-Time Communication:
- Socket.IO  

### ☁️ Deployment:
- Vercel  

---

## ⚙️ Setup

### 🖥️ Setup Client

```bash
cd client
npm install
npm run dev
⚙️ Setup Server
bash
Copy
Edit
cd server
npm install
npm run start
🔐 Environment Variables
Create a .env file in both the client and server directories.

For server (server/.env):
env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
For client (client/.env):
env
Copy
Edit
VITE_BACKEND_URL=http://localhost:5000
⚡ Socket.IO Integration
This project uses WebSockets via Socket.IO to enable real-time messaging functionality between users.

🔄 Client Emits/Receives:
sendMessage: Emits when a user sends a message.

receiveMessage: Listens for incoming messages in real time.

newUser: Emits when a new user connects.

🖥️ Server Handles:
Active user tracking: Maintains a list of connected users.

Real-time message broadcasting: Sends messages to the intended recipients instantly.

User connection and disconnection: Tracks when users come online or go offline.


