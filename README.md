# 📱 QR Code Scanner & History Manager

A fast, web-based QR Code Scanner that allows users to scan codes using their device camera and save their scan history securely. This project is built as a Progressive Web App (PWA), meaning it can be installed on mobile devices just like a native app.

🔗 **Live Demo:** [https://qr-code-scanner-b6d67.web.app](https://qr-code-scanner-b6d67.web.app)

## ✨ Features

* **Real-time Scanning:** Instantly detects and decodes QR codes using the device camera.
* **User Authentication:** Secure login system to personalize the experience.
* **Scan History:** Automatically saves scanned links and text to the user's account dashboard.
* **PWA Support:** Can be installed on Android and iOS home screens for a full-screen app experience.
* **Responsive Design:** Works smoothly on desktop, tablets, and mobile phones.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript
* **Backend/Hosting:** Google Firebase (Hosting & Authentication)
* **Scanning Library:** HTML5-QRCode (or whichever library you used, e.g., jsQR)

## 🚀 How to Run Locally

If you want to run this project on your own computer:

1.  **Prerequisites:**
    * Install Node.js
    * Install Firebase CLI: `npm install -g firebase-tools`

2.  **Clone or Download the project:**
    * Download the files to a folder (e.g., `scanner`).

3.  **Login to Firebase:**
    ```bash
    firebase login
    ```

4.  **Initialize the Project:**
    ```bash
    firebase init hosting
    ```

5.  **Deploy to Live Site:**
    ```bash
    firebase deploy
    ```

## 📱 How to Install on Mobile (PWA)

1.  Open the [Live Link](https://qr-code-scanner-b6d67.web.app) in Chrome (Android) or Safari (iOS).
2.  **Android:** Tap the prompt "Add to Home Screen" or install from the browser menu.
3.  **iOS:** Tap the "Share" button -> "Add to Home Screen".
4.  The app will appear on your device and launch in full-screen mode.

## 🔒 Safety & Privacy

This application uses Google Firebase for secure authentication. We do not share personal data with third parties. The camera is accessed only for scanning purposes with user permission.

---
*Created by Nadimul*
