## Expense Tracker Application 

This is a Mern Stack based expense tracker Application
The front end was built using the React.js
 Then backend incorporates the Express.js and 
 Next.js. 
 The database management was done via Mongodb
using the Mongoose framework . 



# 💰 Expense Tracker (MERN Stack)

A full-stack Expense Tracker web application built using the **MERN stack** (MongoDB, Express, React, Node.js). This app allows users to track their daily expenses, categorize them, and monitor their financial health.

---

## 🧾 Features

- User Authentication (Register/Login)
- Add, Edit, Delete Transactions
- View all income and expenses
- Filter by date or category
- Responsive UI
- RESTful API using Node.js and Express
- MongoDB for storing user and transaction data

---

## 🛠️ Tech Stack

### Frontend:
- React
- Axios
- React Router DOM
- Bootstrap / Tailwind (optional)

### Backend:
- Node.js
- Express.js
- MongoDB with Mongoose
- JSON Web Tokens (JWT) for Authentication
- Bcrypt for password hashing
- dotenv for environment variable management
- CORS and Morgan for middleware

---

## 📁 Project Structure

expense-tracker/
│
├── backend/ # Express backend
│ ├── config/ # DB connection setup
│ ├── controllers/ # Logic for API routes
│ ├── middleware/ # Auth middleware
│ ├── models/ # Mongoose schemas
│ ├── routes/ # API endpoints
│ ├── .env # Environment variables
│ ├── server.js # Main entry point
│ └── package.json
│
├── frontend/ # React frontend
│ ├── public/
│ ├── src/
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # Page views (Dashboard, Login, etc.)
│ │ ├── App.js
│ │ ├── index.js
│ │ └── utils/
│ └── package.json
│
└── README.md

## Setting Up the backend 

cd backend
npm install


##Create a .env file:


PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Start backend server:


npm start
Runs on http://localhost:5000


## Setting uo the frontend 

cd frontend
npm install
npm start
Runs on http://localhost:3000










