# 🐾 WarmPaws - Winter Pet Care Platform

A modern, responsive web application designed to provide comprehensive winter care services for pets. Built with React, Tailwind CSS, and Firebase to ensure pets stay warm, safe, and healthy during the cold months.

**Live Link:** https://warm-paws-bd.netlify.app/

## ✨ Features

### 🎯 Core Functionality
- **🔐 User Authentication** - Secure login/signup with Firebase Auth
- **🐕 Pet Service Booking** - winter care services
- **👤 User Profiles** - Manage personal profile
- **📱 Responsive Design** - Optimized for all devices
- **🎨 Modern UI/UX** - Beautiful winter-themed interface

### ❄️ Winter-Specific Features
- Winter coat fitting services
- Paw protection treatments
- Indoor warm bed setups
- Cold weather nutrition consultation
- Emergency winter vet care

## 🛠️ Tech Stack

### Frontend
- **React** - Latest React with concurrent features
- **Vite** - Fast build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **DaisyUI** - Component library for Tailwind CSS

### Backend & Auth
- **Firebase 12** - Backend services and authentication
- **Firebase Auth** - User management and security

### Additional Libraries
- **React Router DOM** - Client-side routing
- **Swiper** - Modern slider/carousel
- **AOS** - Scroll animations
- **React Toastify** - Notification system
- **Animate.css** - text animation
- **React Icons** - Button and text icon

---

## 📦 Installation

Follow these steps to set up **WarmPaws** locally:

### ✅ Prerequisites
- Install [Node.js](https://nodejs.org/) (v16+ recommended)
- Install npm (comes with Node.js)
- A Firebase project (for authentication & backend services)

---

### 🟩 1) Clone the Repository
```bash
git clone https://github.com/its-dev-naeem/pet-care-in-winter.git
cd warm-paws
```
### 🟦 2) Install Dependencies
```bash
npm install
```
### 🟧 3) Configure Environment Variables

Create a .env file in the root directory and add your Firebase credentials:

```bash
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```
⚠️ Note: All environment variables must start with VITE_ for Vite to recognize them.

### 📦 5) Build for Production
```bash
npm run build
```
Build files will be generated in the dist/ folder.

---

## 🚑 Troubleshooting

| Issue              | Fix                                                                 |
|--------------------|---------------------------------------------------------------------|
| ❗ CORS error       | Add `app.use(cors())` in backend                                    |
| ❗ MongoDB error    | Add your IP → MongoDB Atlas IP Whitelist (`0.0.0.0/0` for development) |
| ❗ Firebase error   | Ensure all env variables start with `VITE_`                         |
| ❗ Env not loading  | Restart server/client                                               |
| ❗ Module errors    | Delete `node_modules` and run `npm install` again                   |

---


## 🙋 Contact
📧 Email: md.abu.naeem786@gmail.com  
💻 GitHub: [its-dev-naeem](https://github.com/its-dev-naeem)

