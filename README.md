# CartCraze 🛒

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js](https://img.shields.io/badge/Node.js-v18-green)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-v18-blue)](https://reactjs.org/)

**CartCraze** is a full-stack e-commerce web application built using the MERN stack (MongoDB, Express.js, React, Node.js) and Redux for state management. It provides a seamless online shopping experience with features like product catalog management, user authentication, secure payment processing, and order tracking.

---

## Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

---

## Features
- User Authentication (Sign up, Login, Logout)
- Product Catalog (Add, View, Filter, and Search Products)
- Shopping Cart & Checkout
- Order Management & Tracking
- Customer Reviews & Ratings
- Payment Integration:
  - **PayPal**
  - **Stripe** (Test Mode)
- Admin Dashboard for managing products and orders
- Responsive design for mobile and desktop

---

## Tech Stack
- **Frontend:** React, Redux, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Atlas)
- **Authentication:** JWT (JSON Web Tokens)
- **Payment:** PayPal, Stripe (Test Mode)
- **Version Control:** Git & GitHub

---

## Getting Started

### Prerequisites
- Node.js >= 18
- npm >= 9
- MongoDB Atlas account or local MongoDB

### Installation

1. Clone the repository:

git clone https://github.com/abhayshuklaofficial10-oss/CartCraze_using_mern_stack_redux.git
cd CartCraze

cd backend
npm install

cd ../frontend
npm install

Create a .env file in backend:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PAYPAL_CLIENT_ID=your_paypal_client_id
STRIPE_SECRET_KEY=your_stripe_secret_key

Start the development server:

Backend:

cd backend
npm run dev

Frontend:
cd frontend
npm start

Project Structure
CartCraze/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   ├── .env
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   └── App.js
│   └── package.json
├── README.md
└── package.json




