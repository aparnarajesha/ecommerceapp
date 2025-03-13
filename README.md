🛒 Flutter E-Commerce App

A fully functional E-commerce application built using Flutter, featuring user authentication, product browsing, search functionality, a cart system, and a seamless checkout experience.



## Features

-  **User Authentication** (Login/Register with Reqres API)
- **Product Listing** with Infinite Scrolling
- **Product Details Page** (Images, Description, Ratings)
- **Search Functionality** for Easy Navigation
- **Shopping Cart & Checkout System**
- **State Management** using Provider
- **REST API Integration** (FakeStore API for products, Reqres API for authentication)
- **Local Storage Support** using SharedPreferences

---
#Demo:

[![Watch the video](https://youtu.be/DPsdoq8Hz5s?si=S_jA4skaqBMZb6BV)]https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

## 📂 Folder Structure

```
📦 ecommerce_app
 ┣ 📂 models             # Data models
 ┣ 📂 providers          # State management (Auth, Cart, Products)
 ┃ ┣ 📜 auth_provider.dart
 ┃ ┣ 📜 cart_provider.dart
 ┃ ┗ 📜 product_provider.dart
 ┣ 📂 screens            # UI Screens
 ┃ ┣ 📜 cart_screen.dart
 ┃ ┣ 📜 checkout_screen.dart
 ┃ ┣ 📜 home_screen.dart
 ┃ ┣ 📜 login_screen.dart
 ┃ ┣ 📜 product_detail_screen.dart
 ┃ ┣ 📜 product_list_screen.dart
 ┃ ┣ 📜 register_screen.dart
 ┃ ┗ 📜 search_screen.dart
 ┣ 📂 services           # API & Authentication Services
 ┃ ┣ 📜 api_service.dart
 ┃ ┗ 📜 auth_service.dart
 ┣ 📂 utils              # Helper functions and utilities
 ┣ 📂 widgets            # Reusable UI Components
 ┃ ┣ 📜 product_card.dart
 ┃ ┗ 📜 search_bar.dart
 ┣ 📜 main.dart          # App entry point
 ┣ 📜 pubspec.yaml       # Dependencies and configurations
 ┗ 📜 README.md          # Project Documentation
```

---

## 🔹 Login Credentials

This app uses the **Reqres API** for authentication. Use the following credentials:

- **Email:** `eve.holt@reqres.in`
- **Password:** `pistol`

⚠ Other credentials will not work unless integrated with a custom backend.

For a custom backend, ensure it supports the following fields:

- **Name**
- **Email**
- **Phone Number**
- **Password**

---

## 🛠 How to Run the App

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/flutter-ecommerce-app.git
cd flutter-ecommerce-app
```

### 2️⃣ Install Dependencies
```bash
flutter pub get
```

### 3️⃣ Run the App
```bash
flutter run
```

---

## 🔧 Technologies Used

- **Flutter (Dart)** – UI Framework
- **Provider** – State Management
- **Reqres API** – Authentication
- **FakeStore API** – Product Data
- **SharedPreferences** – Local Storage

---

## 📜 License

This project is **open-source** and available for educational purposes. Feel free to modify and enhance it!

---

## 💡 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

⭐ If you found this project helpful, consider starring the repository!



📧 Contact
👤 Your Name: Aparna
📧 Email: aparnarajeshapzz@gmail.com
