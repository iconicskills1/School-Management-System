# 📘 School Management System

## 📌 Overview
This project is a **School / College Administration System** built using **n8n** and **PostgreSQL Database**.

It provides an automated, form-based interface to manage:
- User authentication (login system)
- Student data entry
- Core school operations through interactive workflows

---

## 🌐 Live Demo
The project is already deployed online and can be accessed here:

👉 https://n8n-kpkchfgx.ap-southeast-1.clawcloudrun.com/form/14e9a3b3-c042-43fb-86d7-ea30a05e7d81

### 🔑 Test Credentials (Admin)
- **Username:** `adnan-aslam`
- **Password:** `test12345`

### 🔑 Test Credentials (User)
- **Username:** `usman-aslam`
- **Password:** `test`

---

## 🚀 Features

### 🔐 1. Login System
- Secure login form with username and password
- Error handling for incorrect credentials
- Success screen displaying:
  - Teacher name
  - School name
  - Campus

---

### 🏫 2. School Management Menu
After login, users can choose:
- Manage Student Attendance
- Manage Student Fee
- Manage Student Results
- Find Student
- Manage School System
- Change Login
- Exit

---

### 👨‍🎓 3. Student Management
- Add new student records via form
- Fields include:
  - Student ID, Name, DOB
  - Guardian details
  - Contact & Email
  - Class, Session, Course

- Automatically tracks:
  - Status (Active)
  - Updated by (logged-in user)

---

### 🔄 4. Exit Handling
- User can type:
  - `exit` or `quit`
- Workflow exits gracefully

---

## 🏗️ Workflow Architecture
Main components:
- **Form Trigger Nodes** → User interaction
- **IF / Switch Nodes** → Logic control
- **Form Nodes** → Data collection and display
- **Webhook-based flows** → Process automation

---

## 🛠️ Technologies Used
- n8n
- PostgreSQL Database (for record keeping)
- Webhook-based form system

---

## ▶️ Usage
1. Open the live demo link  
2. Login using provided credentials  
3. Select desired operation  
4. Perform tasks  

---

## ⚠️ Notes
- Some nodes may be disabled by default  
- Ensure proper configuration before deployment  
- This version focuses on core workflow functionality only  

---

## 👨‍💻 Author
**Engr. Adnan Aslam**  
📧 iconicskills1@gmail.com  

---

## 📜 License
This project is for educational and demonstration purposes.
