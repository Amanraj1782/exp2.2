# 📘 Experiment 2.1 – Banking API & Middleware Systems

## 📌 Overview

This project is a combined implementation of three important backend concepts using **Node.js and Express**:

* **2.2.1** → Express Middleware (Logging & Authentication)
* **2.2.2** → JWT Authentication for Banking API
* **2.2.3** → ACID Transactions using MongoDB

All experiments are integrated into a **single web interface with tabs** for easy demonstration.

---

## 🚀 Features

### 🔹 Experiment 2.2.1 – Middleware

* Custom logging middleware
* Authentication middleware
* Protected routes
* Error handling
* Request-response pipeline

---

### 🔹 Experiment 2.2.2 – JWT Authentication

* User registration & login
* JWT token generation
* Protected banking routes
* Balance check & deposit
* Secure API access

---

### 🔹 Experiment 2.2.3 – ACID Transactions

* MongoDB transactions using Mongoose
* Rollback on failure
* Data consistency & integrity
* Transaction logging
* Safe money transfer

---

## 🖥️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (for ACID transactions)
* **Authentication:** JSON Web Tokens (JWT)

---

## 📁 Project Structure

```
project/
│
├── server.js
└── public/
    └── index.html
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone or Download Project

```bash
git clone <your-repo-link>
cd project
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

---

### 3️⃣ Start Server

```bash
node server.js
```

---

### 4️⃣ Open in Browser

```
http://localhost:3000
```

---

## 🧪 How to Use

### ▶ Middleware (2.2.1)

* Click Public → access open route
* Click Protected → requires token

---

### ▶ JWT (2.2.2)

* Register user
* Login → receive token
* Use token to access secure routes

---

### ▶ ACID Transactions (2.2.3)

* Create users
* Transfer money
* Failed transactions rollback automatically

---

## 🎯 Learning Outcomes

* Understanding of Express middleware
* Implementation of JWT authentication
* Secure API design
* MongoDB transaction handling
* ACID properties in real-world systems

---

## 📚 Key Concepts

* Middleware chaining
* Token-based authentication
* Atomic transactions
* Error handling
* Data consistency

---

## ⚠️ Important Notes

* MongoDB transactions require **Replica Set enabled**
* This project is for **educational/demo purposes**
* In production, use:

  * Environment variables
  * Secure token storage
  * Proper database validation

---

## 💡 Future Improvements

* Add JWT refresh tokens
* Integrate MongoDB in all modules
* Add transaction history UI
* Convert into full banking dashboard

---

## 👨‍💻 Author

**Aman Raj**
B.Tech CSE (3rd Semester)

---

## ⭐ Conclusion

This project demonstrates how backend concepts like **middleware, authentication, and transactions** can be integrated into a single application for real-world use.

---
