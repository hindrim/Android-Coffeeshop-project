# Android-Coffeeshop-project
# ☕ Coffee Shop Selling System (Android App)

An Android-based mobile application that enables users to register, browse coffee products, manage a shopping cart, and complete payments via QR or bank account. The system leverages Java, Android SDK, Material Design, and SQLite for a smooth and responsive user experience.

---

## 📱 Features

- ✅ User registration and login with validation
- 📦 View a catalog of coffee products in a modern grid layout
- 🛒 Add/remove items in a shopping cart
- 💳 Checkout with QR or bank account payment
- 🧾 Order history with future tracking support
- 🗂️ Local database using SQLite for data persistence

---

## 🛠️ Tech Stack

- **Frontend**: Java, Android SDK
- **UI Components**: RecyclerView, Material Design, GridLayout
- **Database**: SQLite (local)
- **IDE**: Android Studio

---

## 🎯 Functional Requirements

- Register and authenticate users securely
- Display coffee items with image, name, price, and description
- Manage cart: add, remove, update quantity
- Complete checkout and return to home
- Track order history (future implementation)

---

## 🧱 Database Schema

### 🧑 Users Table

| Field     | Type     | Size | Null | Constraints   |
|---------- |----------|------|------|---------------|
| id        | int      | 4    | No   | Primary Key   |
| username  | varchar  | 50   | No   |               |
| password  | varchar  | 255  | No   |               |

### ☕ Coffee Items Table

| Field       | Type      | Size | Null | Constraints   |
|-------------|-----------|------|------|---------------|
| id          | int       | 4    | No   | Primary Key   |
| name        | varchar   | 50   | No   |               |
| description | varchar   | 255  | No   |               |
| price       | timestamp | 13   | Yes  |               |
| quantity    | int       | 4    | No   |               |
| image       | varchar   | 255  | Yes  |               |

---

