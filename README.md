
# Lamp-Login-Screen

# 💡 Lamp Login Screen – Jetpack Compose

An animated and interactive login screen built using **Jetpack Compose** featuring a playful lamp character that reacts to user interaction.

Instead of a traditional login UI, this screen introduces a **gamified interaction** where the user pulls a lamp cord to turn on the light and reveal the login form.

---

## ✨ Features




- 🎨 Fully custom UI built with **Jetpack Compose Canvas**
- 💡 Interactive **lamp switch animation**
- 🎭 Animated facial expressions (sad → happy)
- 😢 Tear animation when the lamp is off
- 🙂 Smile and blinking animation when the lamp turns on
- 🔆 Dynamic glow lighting effect
- 🧲 Physics-like drag interaction
- 📱 Responsive login card animation
- 🔐 Email & Password authentication
- 🔑 Google Sign-In integration
- ⚡ Smooth Compose animations

---

## 🧠 Interaction Concept

1. The lamp starts **turned off** and looks **sad**.
2. The user **pulls the cord**.
3. The lamp **turns on**, becomes **happy**, and lights up the screen.
4. The **login form appears**.

This adds personality and emotional feedback to the authentication flow.

---

## 🛠 Tech Stack

- **Kotlin**
- **Jetpack Compose**
- **Canvas API**
- **Material 3**
- **Hilt**
- **Google Sign-In**
- **Navigation Compose**

---

## 🎬 Animations Used

- `animateFloatAsState`
- `InfiniteTransition`
- `Spring animation`
- `Fade + Slide transitions`
- `Custom Canvas drawing`

---

## 📦 Architecture



presentation
└── auth
├── LampLoginScreen
├── LoginCard
├── LampField
└── Canvas Face Renderer


State is managed through **LoginViewModel** using reactive state flows.

---

## 💡 Why This UI?

Login screens are usually boring.

This project explores how **motion, personality, and interaction** can improve the first impression of an app.

The lamp behaves like a small character that reacts to the user.

---

## 📸 Preview

Lamp Off (Sad)  
Lamp On (Happy + Login Form)

---
## 🎬 Demo

https://github.com/user-attachments/assets/0c0fb0f8-0ec5-4615-9609-60a3e2df5e06

---

## 🚀 Future Improvements

- Finger tracking animation for the cord
- Sound effects when switching the lamp
- Face reacting to typing errors
- More expressive emotions

---

## 👨‍💻 Author

**ElSharif Shaban**

Android Developer  
Passionate about building creative UI experiences with Jetpack Compose.
