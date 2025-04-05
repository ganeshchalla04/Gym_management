# 💪 Gym Management Web Application

A modern, responsive web app built using **HTML, CSS, JavaScript**, and **Firebase**, designed to simplify gym operations and replace paper receipts. This project is perfect for gym owners and members to manage bills, notifications, and profiles in a secure and user-friendly way.

---

## 🚀 Features

### 🛠 Admin Panel
- Secure login
- Add/update/delete gym members
- Generate digital payment receipts
- Send announcements or fee notifications

### 🙋 Member Panel
- Secure login
- View digital payment receipts
- Receive important notifications from the gym

---

## 🔧 Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend & Auth:** Firebase Authentication
- **Database:** Firebase Firestore

---

## 🗂 Folder Structure

gym-app/ 
│ 
├── index.html # Redirect to login 
├── login.html # Login page 
├── admin.html # Admin dashboard 
├── member.html # Member dashboard 
├── styles.css # Global styles 
├── firebase-config.js # Firebase configuration 
└── assets/ # For images or icons (add as needed)
---

## ⚙️ Firebase Setup Instructions

1. Go to [Firebase Console](https://console.firebase.google.com)
2. Create a new project
3. Click “Add App” and choose the web option
4. Copy the config and paste it in `firebase-config.js`
5. Enable **Email/Password Authentication**
6. Create Firestore Database in **test mode**
7. Manually add an admin user (e.g. `admin@gym.com`) in Authentication

---

## 🧪 Test Users

| Role    | Email           | Password  |
|---------|------------------|-----------|
| Admin   | admin@gym.com    | yourpass  |
| Member  | member@example.com | yourpass  |

---

## 🧱 Firestore Collections

- `members`: `{ name, email }`
- `bills`: `{ email, amount, date }`
- `notifications`: `{ email, message, date }`

---

## 🌱 Future Enhancements

- 💊 Supplement Store Module
- 🍎 Nutrition/Diet Plans
- 🏋️ Personal Trainer Booking
- 🧾 Export bills to PDF
- 📊 Admin Dashboard Analytics
- 📱 Mobile app version (React Native)

---

## 📸 Screenshots

*Coming soon! Add your UI images here.*

---

## 📝 License

This project is open-source and free to use for educational and personal purposes.

---

### 💬 Need help?
Feel free to reach out or open an issue!
