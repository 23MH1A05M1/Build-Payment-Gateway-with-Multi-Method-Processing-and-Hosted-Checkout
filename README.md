# 💳 Multi-Mode Payment Gateway with Hosted Checkout

A **fully Dockerized payment gateway system** inspired by modern platforms like **Razorpay** and **Stripe**.  

This project demonstrates a **complete payment ecosystem** including merchant management, order-based payments, and a **hosted checkout experience** using a scalable, backend-focused architecture.

---

## 📖 Overview

This platform provides:

- Merchant onboarding and authentication  
- Secure order creation and lifecycle management  
- Support for multiple payment methods (UPI & Cards)  
- Hosted checkout flow for end customers  
- Merchant dashboard for tracking transactions and performance  

**Focus Areas:**  
Backend API architecture, payment validation logic, transaction state management, and seamless frontend-backend communication.

---

## 🚀 Core Functionalities

### 🔐 Merchant Operations
- Merchant login and authentication  
- View API credentials (key & secret)  
- Track total transaction count  
- Monitor successful payments  
- Calculate overall payment success rate  
- View complete transaction history  

### 💵 Payment Processing
- UPI payments with strict VPA validation  
- Card payment processing with necessary validations  
- Order-centric payment workflow  
- Clear success and failure transaction states  

### 🛒 Hosted Checkout Experience
- Dedicated hosted checkout page  
- Simple and intuitive payment method selection  
- Secure linkage between orders and payments  

---

## 🧰 Technology Stack

| Layer                  | Technology            |
|------------------------|---------------------|
| Backend APIs           | Node.js, Express     |
| Database               | PostgreSQL           |
| Merchant Dashboard     | HTML, CSS, JavaScript |
| Checkout Interface     | HTML, CSS, JavaScript |
| Containerization       | Docker, Docker Compose |

---

## 🐳 Containerized Architecture

All services run inside Docker containers and can be launched together using **Docker Compose**.

### 🔗 Exposed Ports

| Service                 | Port |
|-------------------------|------|
| Backend API             | 8000 |
| Merchant Dashboard      | 3000 |
| Hosted Checkout         | 3001 |
| PostgreSQL Database     | 5432 |

---

## 🗃️ Database Design

The backend uses a **relational PostgreSQL database** with the following tables:

- **Merchants**  
- **Orders**  
- **Payments**  

### Design Highlights
- Strong foreign-key relationships  
- Indexed columns for faster queries  
- Automatic timestamp tracking  
- Transaction-safe payment records  

---

## 🧪 Preloaded Test Merchant

For easy testing, a demo merchant account is auto-seeded when the application starts.

### 🔑 Dashboard Login
- **URL:** `http://localhost:3000/login.html`  
- **Email:** `test@example.com`  
- **Password:** Any value (authentication bypass for testing)  

---

## ▶️ Getting Started

### Prerequisites
- Docker  
- Docker Compose  

### Start the Application

```bash
docker-compose up -d
````
**Author**
D.Bhagyasri
