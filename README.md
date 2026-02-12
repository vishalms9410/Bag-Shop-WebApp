# 🛍️ Bag Shop – Full Stack E-Commerce Web Application

Bag Shop is a full-stack e-commerce web application built from scratch using Node.js, Express, MongoDB, and EJS.  
The project demonstrates backend architecture, authentication, product management, cart functionality, and MVC design pattern implementation.

---

## 🚀 Tech Stack

**Backend:**
- Node.js
- Express.js
- MongoDB
- Mongoose

**Authentication & Security:**
- JSON Web Token (JWT)
- bcrypt (Password Hashing)
- Express Session

**Frontend:**
- EJS (Embedded JavaScript Templates)
- CSS
- Static Assets (Public Folder)

**Other Tools:**
- Multer (File Uploads)
- connect-flash
- dotenv

---

## 📂 Project Structure

Bag-Shop/
│
├── config/ # Database & configuration files
│ ├── development.json
│ ├── keys.js
│ ├── mongoose-connection.js
│ └── multer-config.js
│
├── controllers/ # Business logic
│ └── authController.js
│
├── middlewares/ # Custom middleware (Authentication)
│ └── isLoggedIn.js
│
├── models/ # Mongoose schemas
│ ├── owner-model.js
│ ├── product-model.js
│ └── user-model.js
│
├── routes/ # Application routes
│ ├── index.js
│ ├── ownersRouter.js
│ ├── productsRouter.js
│ └── usersRouter.js
│
├── public/ # Static files (CSS, Images)
├── views/ # EJS templates
│ ├── partials/
│ ├── admin.ejs
│ ├── cart.ejs
│ ├── createproducts.ejs
│ ├── index.ejs
│ ├── owner-login.ejs
│ └── shop.ejs
│
├── app.js # Entry point
├── package.json
└── package-lock.json


---

## 🔐 Features

- ✅ User Registration & Login
- ✅ Secure Password Hashing using bcrypt
- ✅ JWT-based Authentication
- ✅ Protected Routes using Middleware
- ✅ Product Creation & Management
- ✅ Add to Cart Functionality
- ✅ Bill Calculation (including shipping logic)
- ✅ Order Handling
- ✅ File Upload using Multer
- ✅ MVC Architecture Implementation

🧠 Concepts Implemented
MVC Design Pattern
Authentication & Authorization
MongoDB Data Relationships
Mongoose Populate
Middleware Handling
Session Management
Secure Password Storage
Scalable Folder Structure
