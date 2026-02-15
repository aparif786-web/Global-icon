# 🚀 LuitPro Web App (Firebase Auth + GitHub Pages)

LuitPro is a Progressive Web Application deployed using **GitHub Pages** and integrated with **Firebase Google Authentication**.
This project is designed to work seamlessly inside Android WebView apps built using Sketchware Pro.

---

## 🌐 Live Website

```
https://yourusername.github.io/luitpro
```

---

## 📱 Android App Compatibility

This web app is specially optimized to run inside:

* Android WebView
* Sketchware Pro Apps
* Hybrid Android Apps
* Firebase Embedded Authentication

Unlike Blogger-hosted websites, GitHub Pages allows Firebase Auth to function properly inside WebView without triggering:

> ❌ Unable to process request due to missing initial state

---

## 🔥 Features

* ✅ Firebase Google Sign-In
* ✅ WebView Compatible Login
* ✅ No OAuth Redirect Error
* ✅ Persistent Login State
* ✅ AdMob Safe
* ✅ Cross-Platform Support
* ✅ Lightweight Hosting
* ✅ GitHub Pages Deployment

---

## 🛠️ Tech Stack

* HTML5
* CSS3
* JavaScript
* Firebase Authentication
* GitHub Pages Hosting
* Android WebView (Sketchware Pro)

---

## ⚙️ Firebase Setup

Go to:

Firebase Console → Authentication → Settings

Add the following domain to **Authorized Domains**:

```
yourusername.github.io
```

---

## 📂 Project Structure

```
luitpro/
│
├── index.html
├── firebase.js
├── style.css
├── logo.png
└── README.md
```

---

## 📲 Android Integration (Sketchware)

Inside your MainActivity:

```java
binding.webview1.loadUrl("https://yourusername.github.io/luitpro");
```

Also enable:

```java
webview.getSettings().setJavaScriptEnabled
```

