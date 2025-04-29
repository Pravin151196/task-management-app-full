# Task Management App

A full-stack Task Management web application built with:

- **Frontend**: React + Bootstrap
- **Backend**: Node.js + Express + MongoDB
- **Authentication**: JWT-based login/signup
- **Deployment**: GitHub + Netlify + Render (or your preferred host)

---

# Features

- User registration and login (JWT)
- Create, read, update, delete (CRUD) tasks
- Responsive design for mobile & desktop
- Protected routes for authenticated users
- Background images based on screen size

---

## 🛠️ Setup Instructions

### 🔁 1. Clone the Repository

```bash
git clone https://github.com/Pravin151196/task-management-app-full.git
cd task-management-app-full

## frontend
cd frontend
npm install
npm start

#the React app runs on: http://localhost:3000

##backend
cd ../backend
npm install
node server.js

#the Node.js server on: http://localhost:5000

#.env mongo_uri used with local mongodb compass
PORT=5000
MONGO_URI=mongodb://localhost:27017/taskmanager



