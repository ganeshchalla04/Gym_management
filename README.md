
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
