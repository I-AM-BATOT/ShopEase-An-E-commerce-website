# 🛒 ShopEase – E-Commerce Backend API

## 📌 Project Description

ShopEase is a full-stack e-commerce backend application built using Node.js, Express.js, MongoDB, and JWT authentication. The project provides secure user authentication, product management, category filtering, and order processing APIs for an online shopping platform.

The application is designed with a clean REST API architecture and supports scalable e-commerce functionality.

---

# 🚀 Features

## 🔐 User Authentication System

* User registration and login
* JWT-based authentication
* Password hashing using bcryptjs
* Protected routes middleware
* User profile authentication

---

## 🛍️ Product Management

* Fetch all products
* Product search functionality
* Category-based filtering
* Sorting options:

  * Price Low → High
  * Price High → Low
  * Rating
  * Newest
* Product details API
* Pagination support

---

## 📦 Category System

* Fetch all categories
* Dynamic category filtering
* Slug-based category queries

---

## 🧾 Order Management

* Place orders securely
* Order history per user
* Single order details
* Shipping calculations
* Tax calculations
* Total price generation

---

# 🛠️ Tech Stack

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

## Authentication & Security

* JWT Authentication
* bcryptjs
* dotenv
* Custom Middleware

---

# 📱 API Features

* RESTful API Design
* Secure Authentication
* Protected Endpoints
* Pagination & Filtering
* Error Handling
* JSON Responses

---

# 📂 Project Structure

```bash
shopease-backend/
│
├── config/
│   ├── db.js
│   └── seed.js
│
├── middleware/
│   └── auth.js
│
├── models/
│   ├── User.js
│   ├── Product.js
│   ├── Category.js
│   └── Order.js
│
├── routes/
│   ├── auth.js
│   ├── products.js
│   └── orders.js
│
├── public/
├── server.js
├── package.json
└── .env
```

---

# 🔌 API Endpoints

## Authentication Routes

```http
POST   /api/auth/register
POST   /api/auth/login
GET    /api/auth/me
```

---

## Product Routes

```http
GET    /api/products
GET    /api/products/:id
GET    /api/products/all/categories
```

---

## Order Routes

```http
POST   /api/orders
GET    /api/orders
GET    /api/orders/:id
```

---

# ⚙️ Installation & Setup

## Clone Repository

```bash
git clone https://github.com/your-username/shopease-backend.git
```

## Navigate Into Project

```bash
cd shopease-backend
```

## Install Dependencies

```bash
npm install
```

## Start Development Server

```bash
npm run dev
```

---

# 🔑 Environment Variables

Create a `.env` file in the root directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

# 🗄️ Database Setup

1. Install MongoDB
2. Create a MongoDB database
3. Add your MongoDB URI inside `.env`
4. Start the server

---

# 📸 Screenshots

<img width="1920" height="1080" alt="Screenshot (222)" src="https://github.com/user-attachments/assets/159b4023-93bd-4d10-a2f8-6aae991da97a" />
<img width="1920" height="880" alt="Screenshot (223)" src="https://github.com/user-attachments/assets/c6fb0ddf-c2dd-4663-be6b-806ebd39405e" />
<img width="1920" height="864" alt="Screenshot (224)" src="https://github.com/user-attachments/assets/4a0addf7-4d43-459f-a766-6eb688cf1780" />
<img width="1920" height="873" alt="Screenshot (225)" src="https://github.com/user-attachments/assets/7cb9e1c6-e66a-43e6-8497-677fde94ad3d" />
<img width="1920" height="875" alt="Screenshot (226)" src="https://github.com/user-attachments/assets/bcda6921-8d33-4c85-b01a-8a6d501418bd" />

---

# 🔒 Security Features

* JWT Token Authentication
* Password Hashing
* Protected Routes
* Authentication Middleware
* Environment Variables Protection

---

# 🔮 Future Improvements

* Frontend Integration
* Payment Gateway Integration
* Admin Dashboard
* Product Image Upload
* Wishlist Functionality
* Cart System
* Real-Time Notifications
* Stripe/PayPal Payments

---

# 👨‍💻 Author

Your Name
GitHub: (https://github.com/I-AM-BATOT)

---

# 📌 About

ShopEase is a modern e-commerce backend API project designed for scalable online shopping applications with secure authentication and order management.

---

# 📊 Technologies Used

* JavaScript
* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT
* bcryptjs

---

# ⭐ Resources

* README
* API Documentation
* MongoDB Models
* REST API Routes

---

# ❤️ Conclusion

ShopEase provides a scalable and secure backend foundation for building modern e-commerce applications using Node.js, Express.js, MongoDB, and JWT authentication.
