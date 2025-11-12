// ...existing code...
# ChatDemoApp

Simple chat application with a Node.js + Express + MongoDB backend and a React (Vite + Tailwind) frontend. Real-time messaging is implemented using Socket.IO.

## Features
- User registration and login (JWT)
- Real-time one-to-one messaging with Socket.IO
- Message persistence in MongoDB
- Simple frontend built with Vite and React

## Prerequisites
- Node.js (14+)
- npm
- MongoDB (Atlas or local)

## Environment
Create a `.env` file in the project root with these variables:
```
PORT=3000
MONGODB_CONNECT=<your-mongodb-connection-string>
JWT_SECRET=<your-jwt-secret>
SECURE=development
```

## Install & Run (Development)
1. Install backend dependencies:
   npm install
2. Install frontend dependencies:
   npm install --prefix frontend
3. Run backend (dev):
   npm run dev
4. Run frontend (in a separate terminal):
   npm run dev --prefix frontend

## Build & Start (Production)
- Build frontend and install dependencies:
  npm run build
- Start backend:
  npm start

## API (overview)
- POST /api/auth/*  — authentication (register/login)
- GET/PUT /api/user/* — user operations
- POST/GET /api/message/* — send/read messages

(See backend/rout/ for route files and backend/routControlers/ for handlers.)

## Project Structure
- backend/ — Express server, models, routes, socket code
- frontend/ — React + Vite client

## Notes
- Ensure the MongoDB connection string and JWT secret are correct in `.env`.
- Socket server is initialized in backend/Socket/socket.js.

## License
MIT
```// filepath: c:\Users\PRAKASH\OneDrive\Desktop\chatDemoapp-main\readme.md
// ...existing code...
# ChatDemoApp

Simple chat application with a Node.js + Express + MongoDB backend and a React (Vite + Tailwind) frontend. Real-time messaging is implemented using Socket.IO.

## Features
- User registration and login (JWT)
- Real-time one-to-one messaging with Socket.IO
- Message persistence in MongoDB
- Simple frontend built with Vite and React

## Prerequisites
- Node.js (14+)
- npm
- MongoDB (Atlas or local)

## Environment
Create a `.env` file in the project root with these variables:
```
PORT=3000
MONGODB_CONNECT=<your-mongodb-connection-string>
JWT_SECRET=<your-jwt-secret>
SECURE=development
```

## Install & Run (Development)
1. Install backend dependencies:
   npm install
2. Install frontend dependencies:
   npm install --prefix frontend
3. Run backend (dev):
   npm run dev
4. Run frontend (in a separate terminal):
   npm run dev --prefix frontend

## Build & Start (Production)
- Build frontend and install dependencies:
  npm run build
- Start backend:
  npm start

## API (overview)
- POST /api/auth/*  — authentication (register/login)
- GET/PUT /api/user/* — user operations
- POST/GET /api/message/* — send/read messages

(See backend/rout/ for route files and backend/routControlers/ for handlers.)

## Project Structure
- backend/ — Express server, models, routes, socket code
- frontend/ — React + Vite client

## Notes
- Ensure the MongoDB connection string and JWT secret are correct in `.env`.
- Socket server is initialized in backend/Socket/socket.js.

## License
MIT