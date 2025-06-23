# 🌾 Farmer Government Aided Schemes Web Application

This is a complete web application for farmers to view, apply for, and track government-aided crop schemes. The system includes login and registration, role-based access for **admin** and **users**, and integration with **Firebase Authentication** and **Firestore** database.

---

## 📌 Features

### 👥 Authentication
- User & Admin Login/Register using Firebase Authentication.
- Role-based redirection after login.

### 🧑‍🌾 User Features
- Apply for a government scheme using Scheme ID.
- View available **crops** and **schemes**.
- Check application status (optional to extend).
- Logout functionality.

### 🛠️ Admin Features
- Post new **crops** and **schemes** to database.
- Approve pending applications by Application ID.
- Logout functionality.

---

## 🧱 Technologies Used

- HTML5, CSS3 (with responsive design)
- JavaScript (modular, modern ES6+)
- Firebase (Authentication & Firestore)

---

## 🚀 How to Run Locally

1. Clone this repository or copy all files into a folder.

2. Add your own Firebase config in the `<script type="module">` section:
   ```javascript
   const firebaseConfig = {
     apiKey: "YOUR_API_KEY",
     authDomain: "YOUR_AUTH_DOMAIN",
     projectId: "YOUR_PROJECT_ID",
     storageBucket: "YOUR_BUCKET",
     messagingSenderId: "YOUR_SENDER_ID",
     appId: "YOUR_APP_ID"
   };
