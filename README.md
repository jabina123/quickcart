# QuickCart eCommerce Platform

**QuickCart** is a modern eCommerce web application built using the **MERN stack** (MongoDB, Express, React, Node.js) and **Redux** for state management. The design follows a clean blue-and-white theme with Tailwind CSS.

## 🚀 Features

- User registration and login with JWT
- Product listing with search, filters, and pagination
- Detailed product pages with ratings and reviews
- Shopping cart functionality
- Checkout process with shipping and payment options
- Admin dashboard for managing products, orders, and users
- Order history and profile management for customers
- PayPal integration for secure payments
- Mobile-responsive UI using Tailwind CSS

##  Author

- **Name:** Jabeena  
- **Location:** Qatar  
- **Project Purpose:** Final project for MERN Stack course

## 🛠 Tech Stack

- Frontend: React + Redux Toolkit + Tailwind CSS
- Backend: Node.js + Express
- Database: MongoDB (Mongoose)
- Authentication: JWT
- Payment Integration: PayPal

## 📦 Setup Instructions

### Environment Variables

Create a `.env` file in the root folder and add:

```env
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PAYPAL_CLIENT_ID=your_paypal_client_id
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

You can deploy this app to platforms like Vercel, Render. Be sure to build the frontend before deploying.



### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

```
Sample User Logins

admin@example.com (Admin)
123456

jane@example.com (Customer)
123456
```

## License

This project is open-source and maintained by Jabeena.