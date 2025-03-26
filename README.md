# 🏆 Loyal - ASP.NET MVC Web Application

![.NET Version](https://img.shields.io/badge/.NET-6.0-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)
![Status](https://img.shields.io/badge/Status-Active-blue.svg)

## 📌 Project Overview

**AdMod** is a modern **ASP.NET MVC** web application designed for **user authentication, admin management, and Partner handling**. 


1. This project streamlines interactions between Users, Admins, and Partners through an intuitive dashboard system. Below is the flow of functionality:

2. User Request Submission: Users can input their personal details and submit a request, which is forwarded to the Admin Dashboard.

3. Admin Review and Decision: Admins have the authority to review incoming requests and decide whether to accept them. If accepted, the User can proceed to submit an Offer.

4. Offer Management: Once an Offer is submitted by the User, Admins can either accept or reject the Offer based on their discretion.

Partner Dashboard Integration: Upon Admin approval of an Offer, the Offer becomes visible in the Partner Dashboard. Partners can then access and utilize the approved Offer as needed.
It integrates **Entity Framework** for database operations and provides a **secure, scalable, and user-friendly** experience.

---

## 🚀 Features

✅ **User Authentication** – Login, Registration, and Role-based Access  
✅ **Admin Panel** – Manage users, view reports, and handle requests  
✅ **Database Integration** – Uses **Entity Framework (EF)** with **SQL Server**  
✅ **Session Management** – Stores user sessions for security and efficiency  
✅ **Secure & Scalable** – HTTPS, session timeouts, and database encryption  

---

## 🛠️ Technologies Used

| Technology       | Purpose                       |
|-----------------|--------------------------------|
| **ASP.NET MVC**  | Backend Framework            |
| **Entity Framework** | Database Handling         |
| **SQL Server**   | Relational Database          |
| **Bootstrap & jQuery** | Frontend UI & Styling   |
| **Kendo UI (if used)** | Advanced UI Components |

---

## ⚙️ Installation Guide

### **📌 Prerequisites**
Make sure you have the following installed:
- [Visual Studio 2022+](https://visualstudio.microsoft.com/)
- [.NET 6 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/6.0)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- [Git](https://git-scm.com/)


### **📌 Configure the Database**
Open appsettings.json and update the database connection:

---
"ConnectionStrings": {
   "Default": "Server=YOUR_SERVER;Database=YOUR_DB_NAME;Trusted_Connection=True;Encrypt=false;"
}

---

**The application will start at https://localhost:5001/**

---

**Login via https://localhost:5001/Home/Login**

---

### **🔄 API Endpoints**

---
/Home/Login	GET	User Login Page
---
/Admin/Dashboard	GET	Admin Dashboard
---
/Request/New	POST	Submit New Request
---

### **📞 Need Help?**
💬 Contact the author at ashishbanerjee2027@gmail.com
