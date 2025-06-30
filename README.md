# InternIntelligence_ProjectName.# Firebase Login Page 🔐

This project is a simple and responsive **login page** powered by **Firebase Authentication**, built using HTML, CSS, and JavaScript. It allows users to log in securely using their email and password credentials.

---

## 🔧 Features

- Email & password authentication using Firebase
- Form validation with friendly error handling
- Password visibility toggle option
- Login success message with redirection
- Fully responsive user interface
- All code (HTML, CSS, JavaScript) combined in a single `index.html` file for simplicity

---

## 🚀 Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- [Firebase Authentication (v9 compat)](https://firebase.google.com/docs/auth)

---

## 🔐 Firebase Configuration

Firebase is initialized using the following configuration:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID",
};

/firebase-login-task/
├── index.html      ← Contains all HTML, CSS, and JavaScript in one file
└── README.md       ← Project documentation (this file)
