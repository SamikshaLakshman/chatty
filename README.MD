# Chatty – Real-Time Chat Application

Chatty is a full-stack real-time messaging application built to understand and implement modern web application architecture, real-time communication, and secure authentication.

The project focuses on clean separation of concerns between frontend and backend, persistent data storage, and low-latency message delivery using WebSockets.

---

## Features

- Secure user authentication using JWT
- One-to-one real-time messaging
- Persistent chat history stored in MongoDB
- Live message updates using Socket.io
- Responsive and minimal UI

---

## Tech Stack

Frontend:
- React (Vite)
- Tailwind CSS
- Axios
- Socket.io-client

Backend:
- Node.js
- Express.js
- MongoDB (Mongoose)
- Socket.io
- JWT Authentication

---

## System Architecture

- REST APIs handle authentication, user management, and message persistence
- WebSockets are used for real-time message delivery
- MongoDB stores users and chat messages
- JWT secures protected routes using middleware

---

## Installation & Setup

Prerequisites:
- Node.js (v18+ recommended)
- MongoDB (local or cloud)

Backend setup:

cd backend
npm install
npm run dev

Create a .env file inside the backend directory:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Frontend setup:

cd frontend
npm install
npm run dev

---

## Testing

- Backend APIs tested using Postman
- Real-time messaging tested using multiple browsers

---

## Learning Outcomes

- Implemented JWT-based authentication and authorization
- Designed RESTful APIs using Express
- Built real-time communication using WebSockets
- Managed global state in React
- Structured a scalable full-stack application

---

## Future Enhancements

- Group chat support
- Read receipts and typing indicators
- File sharing
- Dockerized deployment
- Automated testing

---



This project is for learning and demonstration purposes.

