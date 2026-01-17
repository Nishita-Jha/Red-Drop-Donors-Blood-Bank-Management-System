# 🩸 Red Drop Donors – Blood Bank Management System

Red Drop Donors is a full-stack web application designed to streamline the management of blood donation processes, donor information, and blood stock. The system offers a centralized platform to connect donors, administrators, and beneficiaries in an efficient and user-friendly way.

---

## 📌 Project Overview

Blood banks play a vital role in healthcare by managing, storing, and distributing blood safely. This project helps automate and organize blood donation workflows, making processes like donor registration, blood request handling, and inventory tracking easy and accessible.

With this system, administrators can oversee supplies and requests, while donors can register and contribute to urgent needs — ultimately helping save lives.

---

## ✨ Key Features

### 🧑‍💼 Admin Module
- Secure admin login
- Manage donor and recipient data
- Monitor blood inventory levels
- Approve or reject blood requests

### 🧑‍🤝‍🧑 Donor Module
- Donor registration and login
- Profile management
- View donation history and status

### 🏥 Recipient / User Module
- Register and login
- Request blood units
- Track request status

### 🩹 Inventory Management
- Maintain blood stock by group type
- Real-time tracking of available units

---

## 🛠️ Technology Stack

- **Backend:** Node.js, Express.js  
- **Frontend:** JavaScript, HTML, CSS  
- **Database:** MongoDB  
- **APIs:** RESTful API design  
- **Authentication:** JWT  
- **Version Control:** Git & GitHub

---

## 📁 Project Structure
```
Red-Drop-Donors-Blood-Bank-Management-System/
├── client/   # Frontend client code
├── config/   # Configuration files
├── controllers/   # API logic & controllers
├── middlewares/   # Middleware functions
├── models/   # Database schemas/models
├── routes/   # API route definitions
├── .env   # Environment variables
├── .gitignore
├── package.json
└── server.js   # App entrypoint
```
---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Nishita-Jha/Red-Drop-Donors-Blood-Bank-Management-System.git
cd Red-Drop-Donors-Blood-Bank-Management-System
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Environment Variables
Create a .env file in the project root with the following:
```env
PORT = 5000
MONGO_URI = your_mongodb_connection_string
JWT_SECRET = your_jwt_secret
```

### 4️⃣ Run the Server
```bash
npm start
```
---

## 🧪 Usage

- Visit the frontend (client) to register as a donor or login.
- Admin users can access the admin dashboard to manage all users and blood requests.
- Donors can register their blood group and view donation history.
- Recipients can submit blood requests and check statuses.

---
**⭐ If you found this project helpful, feel free to star the repository !!**
