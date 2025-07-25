# ✨ Fullstack Chat & Video Calling App ✨

A modern, scalable real-time chat and video calling application with authentication, language exchange, and a beautiful themed UI.

---

## Demo App

---

## Highlights

- 🌐 **Real-time Messaging** with Typing Indicators & Reactions
- 📹 **1-on-1 and Group Video Calls** with Screen Sharing & Recording
- 🔐 **JWT Authentication** & Protected Routes
- 🌍 **Language Exchange Platform** with 32 Unique UI Themes
- ⚡ **Tech Stack:** React + Express + MongoDB + TailwindCSS + TanStack Query
- 🧠 **Global State Management** with Zustand
- 🚨 **Error Handling** (Frontend & Backend)
- 🚀 **Free Deployment**
- 🎯 **Built with Scalable Technologies** like Stream
- ⏳ And much more!

---

## Tech Stack
- **Frontend:** React, Zustand, TanStack Query, TailwindCSS, Socket.io-client, Axios
- **Backend:** Node.js, Express, MongoDB (Mongoose), Socket.io, JWT, bcryptjs
- **Other:** Stream (for scalable messaging/video), 32 UI themes

---

## Features
- User registration and login (JWT-based authentication)
- Real-time messaging (Socket.io)
- Typing indicators and message reactions *(if implemented)*
- 1-on-1 and group video calls *(if implemented)*
- Screen sharing and recording *(if implemented)*
- Online users list
- Language exchange platform *(if implemented)*
- 32 unique UI themes *(if implemented)*
- Global state management with Zustand *(if implemented)*
- Error handling (frontend & backend)
- Free deployment ready

---

## Folder Structure
```
chat-app/
  backend/      # Express server, API, WebSocket, MongoDB models
  frontend/     # React app (UI, components, routing)
```

---

## .env Setup

### Backend (`/backend`)
```
PORT=5001
MONGO_URI=your_mongo_uri
STEAM_API_KEY=your_steam_api_key
STEAM_API_SECRET=your_steam_api_secret
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development
```

### Frontend (`/frontend`)
```
VITE_STREAM_API_KEY=your_stream_api_key
```

---

## Running the App

### 🔧 Run the Backend
```bash
cd backend
npm install
npm run dev
```

### 💻 Run the Frontend
```bash
cd frontend
npm install
npm run dev
```

---

## Usage
1. Register a new user via the Sign Up page.
2. Log in with your credentials.
3. Start chatting and video calling with other online users in real time!

---

## Scripts
- **Backend:**
  - `npm run dev` — Start Express server in development mode
- **Frontend:**
  - `npm run dev` — Start React dev server
  - `npm run build` — Build for production

---

