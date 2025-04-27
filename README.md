# 🏨 Hotel Management System - Java (Swing + JDBC + MariaDB)

This is a complete Hotel Management System developed using **Java Swing** for GUI, **JDBC** for database connectivity, and **MariaDB** as the backend database. It supports room booking, customer checkout, receipt generation, UPI payments, and admin features — making it a real-world ready project.

---

## 🔧 Tech Stack

- ✅ Java (Core Java + Swing GUI)
- ✅ JDBC (Java Database Connectivity)
- ✅ MariaDB (Relational Database)
- ✅ iText (for PDF receipt generation)
- ✅ ZXing (for QR code payments)
- ✅ IntelliJ IDE

---

## ✨ Features

### 🛏️ Room Booking
- Book available rooms by entering customer details
- Automatically updates room availability in the database

### 📤 Customer Checkout
- Calculate total bill based on days stayed and room type
- Marks room as available again in the database

### 📄 Receipt Generator (PDF)
- Generates professional PDF receipt using iText library

### 💸 UPI / QR Payment
- Scannable UPI QR code generated for payment simulation
- Payment mode (Cash, UPI, Online) saved in database

### 👨‍💼 Admin Panel
- View all bookings, payments, and customer info in a table
- Can be extended for room rate management and reporting

---

## 📂 Project Structure

HotelManagementSystem/
│
├── src/
│   ├── DBConnection.java
│   ├── HotelApp.java
│   ├── RoomBookingPanel.java
│   ├── CheckoutPanel.java
│   ├── PDFGenerator.java
│   ├── QRPaymentPanel.java
│   └── CustomerTablePanel.java
│
├── lib/                  # External JARs (iText, ZXing etc.)
├── images/               # QR code / logo / UI assets
├── hotel_db.sql          # SQL file to create MariaDB tables
└── README.md             # You're here!



## 🗃️ Database Tables (MariaDB)

- `rooms` – stores room details and availability
- `customers` – stores customer booking info
- `payments` – stores payment method and transaction info

> 📝 All SQL queries are handled using **PreparedStatements** for security.


## 🙌 Author

**BHERUNATH GEHLOT**  
📧 Email: bhanwarm99@gmail.com  
🔗 LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/bherunath-gehlot)  
💻 GitHub: [github.com/bgmali2002](https://github.com/bgmali2002)
