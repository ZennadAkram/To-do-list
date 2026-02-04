# 📝 Flutter To-Do List App

[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter&logoColor=white)](https://flutter.dev/) 
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart&logoColor=white)](https://dart.dev/) 
[![Firebase](https://img.shields.io/badge/Firebase-Platform-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com/) 
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

A modern **cross-platform To-Do List application** built with **Flutter** and **Firebase**.  
It allows users to manage tasks efficiently, receive notifications for scheduled tasks, and securely authenticate using **Google** or **Email & Password**. All tasks are stored in **Cloud Firestore** for real-time updates.

---

## 🔥 Features

### User Features
- ✅ **Add, Edit, and Delete Tasks**
- 🕒 **Scheduled Notifications** for tasks
- 🔎 **Real-time task updates** with Firestore
- 🔐 **Authentication**
  - Google Sign-In
  - Email & Password
- 📱 **Cross-platform support**: Android, iOS, Web
- 🌙 **Dark mode support** (if implemented)

### Backend / Firebase Features
- ☁️ **Firestore**: Stores tasks and user data
- 🔔 **Firebase Cloud Messaging**: Task notifications
- 🔑 **Firebase Authentication**: Secure login
- 📊 Real-time synchronization across devices

---

## 🛠️ Technologies Used

[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter&logoColor=white)](https://flutter.dev/)  
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart&logoColor=white)](https://dart.dev/)  
[![Firebase](https://img.shields.io/badge/Firebase-Platform-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com/)  
[![Firestore](https://img.shields.io/badge/Cloud%20Firestore-NoSQL-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com/products/firestore)  
[![Firebase Auth](https://img.shields.io/badge/Firebase%20Auth-Google%20%7C%20Email-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com/products/auth)  
[![Notifications](https://img.shields.io/badge/Notifications-Scheduled-blue?logo=bell&logoColor=white)](#)  

---

## ⚙️ Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/ZennadAkram/To-do-list.git
```

2. **Install Flutter dependencies**
```bash
cd flutter-todo-app
flutter pub get
```

3. **Firebase Setup**
-Create a Firebase project
-Add Android/iOS/Web app in Firebase
-Download google-services.json (Android) or GoogleService-Info.plist (iOS) and place them in your project
-Configure Firebase in main.dart using Firebase.initializeApp()

4.**Run the app**
```bash
flutter run

