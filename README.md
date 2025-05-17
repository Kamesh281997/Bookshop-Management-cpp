# 📚 Bookshop Management System

A command-line based Bookshop Management System implemented in **C++**, featuring user authentication, book inventory (hardcopy & softcopy), and operations like rent, buy, and stock tracking.

---

## 🚀 Features

- 🔐 **User Authentication**
  - Register/Login with password and security key
  - Credential management via `newpassword.txt`

- 📖 **Book Management**
  - Add, update, delete, and search books
  - Rent and buy books with price calculation
  - Support for both hardcopy and softcopy books

- 🛍️ **Sales & Rentals**
  - Rent calculation by days
  - Delivery and discount logic for purchases

- 🧾 **Console UI**
  - Simple menu-driven interface using control panel

---

## 🧱 Code Structure

- **`main.cpp`**: Contains all the logic for the system
- **Classes**:
  - `security`: Handles login and credential operations
  - `Bookshop`: Manages the control panel interface
  - `HAdd_Books` / `SAdd_Books`: Manage hardcopy/softcopy book operations

---

## 💻 How to Run

### 🧰 Prerequisites

- Windows OS (for `conio.h` and `system("cls")`)
- A C++ compiler like `g++` or MSVC

### 🛠️ Compile & Run

Using `g++`:

```bash
g++ main.cpp -o bookshop
./bookshop
