# 🏢 Workplace Access — Barcode Generator System

A simple, lightweight web app that allows employees to generate workplace access barcodes for **clocking in, clocking out, and managing breaks**.

This project focuses on:

- Practical, real-world workplace use
- Clean and intuitive UI
- Simple local authentication (no backend)
- Reliability and ease of use for non-technical users

It runs entirely in the browser — no database server, no frameworks, no installs.

---

## ✨ Features

### 🔐 User Accounts

Employees can create an account with:

- Full name  
- Username  
- Password  

Each user automatically receives a unique **Employee ID** on signup.

User accounts are stored in the browser using `localStorage`.

---

### 🎫 Barcode Generation

Once logged in, a user can generate barcodes for:

- ✅ Entry — Clock In  
- 🚪 Exit — Clock Out  
- ☕ Break — Start  
- 🔁 Break — End  

Each barcode contains:

- Employee ID  
- Selected action  
- Timestamp  
- Unique barcode ID string  

Barcodes are generated using **JsBarcode (CODE128 format)** and can be:

- Viewed on screen  
- Printed directly from the app  

---

### 👤 Personalized Dashboard

After login, the dashboard displays:

- Employee name  
- Employee ID  
- The latest generated barcode details  

The interface is built to feel modern, professional, and easy to navigate.

---

## 🛠️ Tech Stack

- **HTML** – Structure and layout  
- **CSS** – Modern, responsive UI  
- **JavaScript** – App logic and interactions  
- **JsBarcode** – Barcode generation (`CODE128`)  
- **LocalStorage** – Persistent user accounts in the browser  

No backend. No external database. 100% front-end.

---

## 🚀 How It Works

1. User signs up or logs in  
2. Their employee profile is displayed (name + employee ID)  
3. They choose an action (Entry / Exit / Break Start / Break End)  
4. A unique barcode is generated using:
   - Employee ID  
   - Action type  
   - Timestamp  
5. The barcode and details are displayed and can be printed

Everything happens locally in the browser.

---

## 🎨 UI & Design

The UI uses:

- Gradient background  
- Card-style layout  
- Rounded corners and soft shadows  
- Clear typography and spacing  

The goal is to make the app feel like something that could realistically be used at a workplace front desk or kiosk.

---

## 🧩 Why This Project

This project was built to show:

- Front-end authentication flows  
- Local data storage using `localStorage`  
- Integration with a third-party library (JsBarcode)  
- Thoughtful UX for non-technical users  

It’s designed as a **portfolio-ready** project that mimics a real internal tool a company might use for staff access or time tracking.

---

## 📌 Possible Future Enhancements

Some ideas to extend this project:

- Admin dashboard to view logs and activity  
- Backend integration (e.g., Node/Express + database)  
- Role-based access (Admin / Employee)  
- QR code support alongside barcodes  
- Exportable attendance reports  
- Mobile-friendly scanner UI  

---

## 👤 Author

**Muhammad Khuzaima Wajid**  
Front-End Developer · Workplace & Productivity Tools

---

