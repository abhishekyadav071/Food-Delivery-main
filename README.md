# 🍅 TOMATO - Food Delivery Web Application (MERN)

A full-stack food ordering web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The platform provides a seamless experience for users to browse food, place orders, and manage their cart, along with an admin panel for managing products and orders.

---

## 🚀 Live Demo

* 🌐 User Panel: https://food-delivery-frontend-s2l9.onrender.com/
* 🛠️ Admin Panel: https://food-delivery-admin-wrme.onrender.com/

---

## ✨ Features

### 👤 User Features

* User Signup & Login (JWT Authentication)
* Browse Food Items
* Add to Cart & Remove Items
* Place Orders
* Secure Payment Integration (Stripe)
* Order History

### 🛠️ Admin Features

* Add / Update / Delete Products
* Manage Orders
* Role-based Access Control

---

## 🛠️ Tech Stack

**Frontend:**

* React.js
* HTML5, CSS3, Bootstrap

**Backend:**

* Node.js
* Express.js

**Database:**

* MongoDB

**Other Tools & Libraries:**

* JWT Authentication
* Bcrypt (Password Hashing)
* Stripe Payment Gateway
* Multer (File Uploads)

---

## 📂 Project Structure

```
Food-Delivery/
│── frontend/   # User React App
│── admin/      # Admin Panel
│── backend/    # Node.js + Express API
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/Food-Delivery.git
cd Food-Delivery
```

---

### 2️⃣ Install dependencies

#### Backend

```
cd backend
npm install
```

#### Frontend

```
cd ../frontend
npm install
```

#### Admin Panel

```
cd ../admin
npm install
```

---

### 3️⃣ Setup Environment Variables

Create a `.env` file in the **backend** folder and add:

```
JWT_SECRET=your_secret_key
SALT=10
MONGO_URL=your_mongodb_connection
STRIPE_SECRET_KEY=your_stripe_key
```

---

### 4️⃣ Run the Application

#### Start Backend

```
cd backend
npm start
```

#### Start Frontend

```
cd frontend
npm start
```

#### Start Admin Panel

```
cd admin
npm start
```

---

## 📸 Screenshots

* Home Page
* Product Listing
* Cart Page
* Login System

(Add your screenshots here)

---

## 💡 Key Highlights

* Full-stack MERN application with real-world features
* Secure authentication using JWT
* Integrated Stripe payment gateway
* Clean and scalable folder structure
* RESTful APIs with proper error handling

---

## 📌 Future Improvements

* Add search & filters
* Improve UI/UX
* Add order tracking system
* Deploy using Docker

---

## 👨‍💻 Author

**Abhishek Yadav**

* GitHub: https://github.com/abhishekyadav071

---

## ⭐ Show Your Support

If you like this project, please give it a ⭐ on GitHub!
