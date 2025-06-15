# 💬 Talkon

**Talkon** is a full-stack real-time chat application built with the **MERN stack** and **Socket.IO**. It features secure authentication, image sharing, user search, and an elegant UI designed for both desktop and mobile.

---

## 🚀 Features

- 🔐 **JWT-based user authentication** - Secure login and registration system
- ⚡ **Real-time messaging** - Instant communication via Socket.IO
- 🖼️ **Image sharing** - Share images seamlessly in chats
- 🧑‍💼 **User profiles** - Customizable profiles with bios
- 🔎 **Search functionality** - Find users quickly and easily
- 📁 **Clean architecture** - Component-based design for maintainability
- 📱 **Responsive design** - Works perfectly on desktop and mobile devices

---

## 🛠️ Tech Stack

### Frontend
- **React.js** - UI library for building interactive interfaces
- **Tailwind CSS** - Utility-first CSS framework for styling
- **React Router** - Client-side routing
- **React Hot Toast** - Beautiful toast notifications

### Backend
- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling

### Real-Time Communication
- **Socket.IO** - Real-time bidirectional event-based communication

### Deployment
- **Vercel** 

---

## ⚙️ Getting Started

### 🖥️ Client Setup

```bash
# Clone the repository
git clone https://github.com/palakverma25/talkon.git

# Navigate to client directory
cd talkon/client

# Install dependencies
npm install

# Start development server
npm run dev
```

### 🔧 Server Setup

```bash
# Navigate to server directory
cd talkon/server

# Install dependencies
npm install

# Start the server
npm run start
```

---

## 🔐 Environment Variables

Create `.env` files in both client and server directories:

### Server Environment Variables (`server/.env`)

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

### Client Environment Variables (`client/.env`)

```env
VITE_BACKEND_URL=http://localhost:5000
```

---

## ⚡ Socket.IO Integration

This project uses WebSockets via Socket.IO to handle real-time messaging between users.

### 📡 Client Events

| Event | Description |
|-------|-------------|
| `sendMessage` | Emitted when a user sends a message |
| `receiveMessage` | Listens for new incoming messages |
| `newUser` | Triggered when a user connects |
| `userDisconnected` | Triggered when a user disconnects |

### 🖥️ Server Responsibilities

- Track online users and their status
- Broadcast messages to appropriate chat rooms
- Handle user connection and disconnection events
- Manage real-time user presence indicators

---


## 🔧 Available Scripts

### Client Scripts
```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run preview      # Preview production build
```

### Server Scripts
```bash
npm run start        # Start production server
npm run dev          # Start development server with nodemon
```

---

## 🚀 Deployment

### Vercel
1. Connect your GitHub repository to Vercel
2. Set environment variables in Vercel dashboard
3. Deploy automatically on push to main branch

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---
## 👨‍💻 Author

**Palak Verma**

**Happy Chatting! 💬✨**
