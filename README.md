# 📝 CRUD Application

This is a full-stack **CRUD (Create, Read, Update, Delete)** application built using the MERN stack (MongoDB, Express.js, React, Node.js). It allows users to perform all CRUD operations with a user-friendly interface and backend API.

## 🚀 Features

- Create new items
- View list of all items
- Edit/update existing items
- Delete items
- Responsive UI
- API-based backend

## 🛠️ Tech Stack

- **Frontend**: React.js, Tailwind CSS (or Bootstrap/CSS Modules)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (using Mongoose)
- **Tools**: Postman for API testing, Git & GitHub for version control

## 📁 Folder Structure

crud-app/
│
├── client/ # React frontend
│ ├── public/
│ └── src/
│ ├── components/
│ ├── pages/
│ └── App.js
│
├── server/ # Express backend
│ ├── models/
│ ├── routes/
│ └── server.js
│
├── .gitignore
├── README.md
└── package.json

## ⚙️ Installation & Setup

## 1. Clone the repository

git clone https://github.com/your-username/crud-app.git
cd crud-app

## 2. Install dependencies for both frontend and backend

For server
cd server
npm install

For client
cd ../client
npm install

## 3. Start the backend server

cd ../server
npm start

## 4. Start the React frontend

cd ../client
npm start

## 5. Connect MongoDB
Make sure MongoDB is running locally or provide a MongoDB Atlas URI in .env file like:
MONGO_URI=mongodb://localhost:27017/crud-app

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first.

## 📃 License
MIT License
