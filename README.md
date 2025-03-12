🛒 Flutter E-Commerce App

A fully functional E-Commerce application built with Flutter and integrated with FakeStore API for product management. The app includes user authentication, product browsing, filtering, cart management, and secure local storage.


---

🚀 Features

User Authentication (Login, Registration, Logout) with token storage

Home Page with featured products and infinite scrolling

Product Detail Page with images, price, description, and ratings

Search Functionality to find products by name

Product Sorting & Filtering by categories, price range, and ratings

Shopping Cart (Add, Remove, Update Quantities)

Secure User Data Storage using Flutter Secure Storage

API Integration with FakeStore API



---

🛠 Tech Stack

Flutter (Dart)

Provider (State Management)

Flutter Secure Storage

REST API Integration



---

Installation

1️⃣ Clone the repository

git clone https://github.com/yourusername/flutter-ecommerce-app.git
cd flutter-ecommerce-app

2️⃣ Install dependencies

flutter pub get

3️⃣ Run the app

flutter run


---

🔹 Step 3: Verify API is Used Correctly

The authentication system is integrated with Reqres API.
🔹 Use the following credentials for testing:

⚠️ If you use any other email/password, authentication will fail.
For a custom backend, ensure it supports name, phone, email, and password.


---

📂 Folder Structure

lib/  
│── main.dart            # App entry point  
│── models/              # Data models (Product, User)  
│── providers/           # State management (Auth, Products, Cart)  
│── screens/             # UI Screens (Login, Home, Product Details, Cart)  
│── services/            # API Services (Auth, Products)  
│── widgets/             # Reusable UI components


---

🔐 Authentication Setup

User authentication is implemented using a custom backend API.

Tokens are securely stored in Flutter Secure Storage for auto-login.



---
License

This project is licensed under the MIT License.
