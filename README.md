# Ecom-portal
Web Project  Description

# 🛒 MERN eCommerce Website

## 📌 Overview

This is a fully functional eCommerce web application built using the **MERN stack** (MongoDB, Express.js, React, Node.js). It features both **user-facing pages** and an **admin dashboard**, with secure password encryption and a responsive design.

> ✅ Created by following a tutorial and customized for real-world eCommerce functionality.

---

## 🚀 Features

- 🔐 **User Authentication** with JWT & bcrypt encryption
- 👨‍💼 **Admin Dashboard** to manage products, users, and orders
- 🛍️ **Product Listings** with search, category filtering & pagination
- 🛒 **Cart and Checkout** flow
- 💳 **Payment Integration** using PayPal
- 📱 **Responsive Design** for all screen sizes

---

## 🛠️ Tech Stack

| Layer      | Technology               |
|------------|---------------------------|
| Frontend   | React, Redux, Tailwind CSS |
| Backend    | Node.js, Express.js        |
| Database   | MongoDB                    |
| Auth       | JWT, bcrypt                |
| Deployment | Vercel / Netlify / Render / Heroku |

---

## 📂 Project Structure

#Backend Setup (/server)
Open your terminal or VS Code.
Navigate to the project directory:
cd Ecom-portal
Move into the backend folder:
cd server
Install backend dependencies:
npm install
Create a .env file in the server folder and add the following:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PAYPAL_CLIENT_ID=your_paypal_client_id
Start the backend server:
npm run dev



#💻 Frontend Setup (/client)
Open a new terminal tab/window.
Navigate to the frontend folder:
cd Ecom-portal/client
Install frontend dependencies:
npm install
Start the frontend app:
npm run dev












