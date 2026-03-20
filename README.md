# 📘 School Management System (n8n Workflow)

## 📌 Overview
This project is a **School / College Administration System** built using **n8n**.

It provides an automated, form-based interface to manage:
- User authentication (login system)
- Student data entry
- Core school operations through interactive workflows

---

## 🌐 Live Demo
The project is already deployed online and can be accessed here:

👉 https://n8n-kpkchfgx.ap-southeast-1.clawcloudrun.com/form/14e9a3b3-c042-43fb-86d7-ea30a05e7d81  

### 🔑 Test Credentials
- **Username:** `adnan-aslam`  
- **Password:** `test12345`  

---

## 🚀 Features

### 🔐 Login System
- Secure login form with username and password  
- Error handling for incorrect credentials  
- Success screen displaying:
  - Teacher name  
  - School name  
  - Campus  

---

### 🏫 School Management Menu
After login, users can choose:
- Manage Student Attendance  
- Manage Student Fee  
- Manage Student Results  
- Find Student  
- Manage School System  
- Change Login  
- Exit  

---

### 👨‍🎓 Student Management
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

### 🔄 Exit Handling
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
- n8n (Workflow Automation Tool)
- Webhook-based form system

---

## 📦 Installation & Setup

### 1. Install n8n
```bash
npm install n8n -g
n8n start
````

### 2. Import Workflow

* Open n8n dashboard
* Go to **Workflows → Import**
* Upload the provided `.json` file

---

### 3. Configure Environment

* Set up any required credentials
* Review workflow settings

---

### 4. Activate Workflow

* Enable required nodes
* Click **Activate**

---

## ▶️ Usage

1. Open the live demo link
2. Login using provided credentials
3. Select desired operation
4. Perform tasks such as:

   * Managing student records
   * Navigating school system options

---

## ⚠️ Notes

* Some nodes may be **disabled by default**
* Ensure proper configuration before deployment
* This version focuses on **core workflow functionality only**

---

## 👨‍💻 Author

**Engr. Adnan Aslam**
📧 [iconicskills1@gmail.com](mailto:iconicskills1@gmail.com)

---

## 📜 License

This project is for educational and demonstration purposes.

Just tell me 👍
```
