# 🚆 Train_Ease – Advanced Railway Ticket Booking System

> 🎯 A full-stack Java web application for railway ticket management and booking, designed for seamless train scheduling, ticketing, and user management.

![Java Badge](https://img.shields.io/badge/Java-Full--Stack-blue?style=flat-square&logo=java)
![License Badge](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Database](https://img.shields.io/badge/Database-MySQL-orange?style=flat-square&logo=mysql)
![Server](https://img.shields.io/badge/Server-Tomcat-yellow?style=flat-square&logo=apachetomcat)

---

## 🧭 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
  - [Admin Module](#-admin-module)
  - [User Module](#-user-module)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Installation & Run Guide](#-installation--run-guide)
- [Screenshots](#-screenshots)
- [Future Enhancements](#-future-enhancements)
- [Contributors](#-contributors)
- [License](#-license)

---

## 📝 Overview

Train_Ease is a Railway Ticket Booking Web Application built using Advanced Java (JSP + Servlets) and MySQL.  
It offers Admin and User modules for managing train schedules, bookings, and user data.  
The project demonstrates strong concepts of MVC architecture, **CRUD operations**, **form validation**, and **role-based authentication**.

---

## ✨ Features

### 👑 Admin Module

| Feature | Description |
|----------|--------------|
| ➕ Add Train | Add new train details including train number, name, route, and schedule |
| ✏ Update Train | Modify train details and timings |
| ❌ Delete Train | Remove outdated train data |
| 🔍 Search Train | Find trains using filters (route, ID, name, etc.) |
| 📄 View Booking Details | View all user bookings with relevant information |

### 🙍‍♂ User Module

| Feature | Description |
|----------|-------------|
| 🏠 Home Page | Dashboard after login with navigation options |
| 🚄 View Train | Display available trains |
| 🔎 Search Train | Search trains by name or route |
| 🎫 Book Ticket | Book train tickets quickly and securely |
| ❌ Cancel Ticket | Cancel booked tickets before departure |
| 🧾 Show Ticket | Display current ticket details |
| 📚 Ticket History | View all previous bookings |
| ℹ About Us | Learn about the project and team |
| 📞 Contact Us | Submit feedback or queries |
| 🚪 Logout | Secure logout functionality |

---

## 🛠 Tech Stack

| Category | Technology |
|-----------|-------------|
| Frontend | HTML, CSS, JavaScript, Bootstrap |
| Backend | Java (JSP + Servlets) |
| Database | MySQL |
| Server | Apache Tomcat |
| Version Control | Git & GitHub |
| License | MIT License |

---

## 📁 Project Structure
```
Train_Ease/
│
├── admin/
│ ├── add_train.jsp
│ ├── update_train.jsp
│ ├── delete_train.jsp
│ ├── search_train.jsp
│ ├── train_details.jsp
│ └── booking_details.jsp
│
├── user/
│ ├── home.jsp
│ ├── menu/
│ │ ├── view_train.jsp
│ │ ├── search_train.jsp
│ │ ├── book_ticket.jsp
│ │ ├── cancel_ticket.jsp
│ │ ├── show_ticket.jsp
│ │ └── ticket_history.jsp
│ ├── about_us.jsp
│ ├── contact_us.jsp
│ └── logout.jsp
│
├── database/
│ └── Railway_Ticket_Book_App_DB.sql
│
├── LICENSE
│
└── README.md

yaml
Copy code
```

---

## ⚙ Installation & Run Guide

### 🧩 Prerequisites
Ensure you have the following installed:
- ☕ Java JDK 8+
- 🐬 MySQL Server
- 🧱 Apache Tomcat 9+
- 🧾 Eclipse IDE / IntelliJ IDEA (with Dynamic Web Project support)
- 🔗 Git (optional for version control)

### 🚀 Steps to Run the Project

| Step | Description |
|------|--------------|
| 1️⃣ Clone Repository | git clone https://github.com/Soubhagya-Kabiraj/Train_Ease.git |
| 2️⃣ Open in IDE | Import as Dynamic Web Project (Eclipse)  |
| 3️⃣ Configure Database | Import **Railway_Ticket_Book_App_DB.sql** into MySQL |
| 4️⃣ Update DB Credentials | In the Java DAO files, configure your database username/password |
| 5️⃣ Deploy on Tomcat | Add project to Tomcat server and start it |
| 6️⃣ Access Application | Open browser and go to http://localhost:8080/Train_Ease |
| 7️⃣ Login as Admin/User | Use sample credentials or register new users |

---

## 📸 Screenshots

## 📌 System Modules

| Module Name | Description |
|------------|------------|
| 🏠 Landing Page Module | Entry point of the application for all users |
| 🧑‍💼 User Registration Module | Allows new users to create an account |
| 🧭 User Dashboard Module | Central hub for accessing user functionalities |
| 👤 User Menu Module | Handles login, authentication, and profile management |
| 📋 Ticket Booking Module | Enables users to search for trains and book tickets |
| 🧾 Ticket Details Module | Displays complete booking and travel information |
| 🖨 Ticket Printing Module | Allows users to download or print booked tickets |
| 📚 Booking History Module | Stores and displays previous booking records |
| 🖥 Admin Dashboard Module | Manages trains, users, and monitors bookings |
| ℹ️ About Us Module | Provides information about the project and development team |


<img width="1907" height="913" alt="Screenshot 2026-02-04 202253" src="https://github.com/user-attachments/assets/ffca4301-e4ba-4b41-84f6-af66dd35f616" />

<img width="1888" height="918" alt="Screenshot 2026-02-04 203111" src="https://github.com/user-attachments/assets/5a56b2ee-7224-427f-a151-47c544206aa6" />

<img width="1891" height="916" alt="Screenshot 2026-02-04 202557" src="https://github.com/user-attachments/assets/9aa70279-51ac-48bf-9b04-b14506b531ad" />

<img width="1904" height="910" alt="Screenshot 2026-02-04 202629" src="https://github.com/user-attachments/assets/52bef12d-3025-41ed-95e8-03e11d4566dc" />

<img width="1903" height="912" alt="Screenshot 2026-02-04 202711" src="https://github.com/user-attachments/assets/b5ae055d-af94-4db5-a98e-84b519798ad9" />

<img width="1883" height="922" alt="Screenshot 2026-02-04 202736" src="https://github.com/user-attachments/assets/b9f048ef-22a4-4460-b138-8aa8e09c1577" />

<img width="1769" height="824" alt="Screenshot 2026-02-04 202807" src="https://github.com/user-attachments/assets/5fc6841a-a824-4e5c-92ce-33e00e2e2cfb" />

<img width="1882" height="913" alt="image" src="https://github.com/user-attachments/assets/706f7429-ebfc-4151-84d1-58f6b35847cd" />

<img width="1905" height="919" alt="Screenshot 2026-02-04 202522" src="https://github.com/user-attachments/assets/d31d12ca-3017-476c-a1a2-c01d0a527258" />

<img width="1904" height="917" alt="Screenshot 2026-02-03 212759" src="https://github.com/user-attachments/assets/17472650-b8ae-478a-bc55-2c09e8773bff" />

---

## 🚀 Future Enhancements

✅ Payment Gateway Integration (Razorpay / Paytm)  
✅ Real-Time Seat Selection UI  
✅ PNR Status Tracking  
✅ Email & SMS Confirmation  
✅ Mobile App Version (Flutter / React Native)

---

## 👥 Contributors

| Name | Role |
|------|------|
| 🧑‍💻 Soubhagya Kabiraj | Full Stack Developer |
| 🎨 Sourav Gorain | Frontend UI Designer |
| 🗄 Khushbu Singh | Database Designer |
| 💻 Shreyashree Banerjee | Frontend Developer |
| 💻 Shreya | Frontend Developer |

---

## 🧾 License

This project is licensed under the *MIT License*.  
See the [LICENSE](LICENSE) file for details.
