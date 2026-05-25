# DVLD – Driving License Management System

A desktop application for managing driving license services, built with **C#**, **WinForms**, **SQL Server**, **ADO.NET**, and **3-Tier Architecture**.

The system is designed to manage people, users, drivers, driving license applications, tests, appointments, local licenses, international licenses, renewals, replacement licenses, and detained licenses.

---

## 📌 Project Overview

**DVLD** stands for **Driving & Vehicle License Department**.

This project simulates a real driving license department system. It helps employees manage the full process of issuing and managing driving licenses, from registering people and applications to scheduling tests and issuing licenses.

---

## 🚀 Features

- People management
- User management
- Login system
- Driver management
- Local driving license applications
- License classes management
- Application types management
- Test types management
- Test appointments
- Test results
- Local license issuing
- International license issuing
- License renewal
- Replacement for lost licenses
- Replacement for damaged licenses
- Detained licenses management
- Release detained licenses
- Search and filtering
- Data validation
- Image handling
- User controls
- Business rules validation

---

## 🧩 Main Modules

### 👤 People Management
- Add, edit, delete, and search people
- Validate national number uniqueness
- Validate required fields
- Handle personal images
- Filter and display people data

### 👥 Users Management
- Create users linked to people
- Edit user information
- Activate or deactivate users
- Manage login information
- Track current logged-in user

### 🚗 Drivers Management
- Manage driver records
- Link drivers with people
- View active licenses count
- Display driver information

### 📄 Applications Management
- Create driving license applications
- Manage application status
- Prevent duplicate active applications
- Track paid fees and application dates

### 🧪 Tests Management
- Vision test
- Theory test
- Practical test
- Schedule appointments
- Save test results
- Handle retake tests

### 🪪 Licenses Management
- Issue local driving licenses
- Issue international driving licenses
- Renew licenses
- Replace lost or damaged licenses
- View license history

### ⛔ Detained Licenses
- Detain a license
- Add fine fees
- Release detained licenses
- Track detain and release information

---

## 🛠️ Technologies Used

- **C#**
- **.NET Framework**
- **Windows Forms**
- **SQL Server**
- **ADO.NET**
- **3-Tier Architecture**
- **Object-Oriented Programming**
- **SQL Queries**
- **User Controls**
- **Delegates & Events**

---

## 🏗️ Architecture

The project follows **3-Tier Architecture**:

```text
Presentation Layer
│
├── Windows Forms UI
├── User Controls
├── Validation
└── User interaction

Business Layer
│
├── Business rules
├── Application logic
├── Validation logic
└── Object-oriented classes

Data Access Layer
│
├── SQL Server connection
├── CRUD operations
├── ADO.NET
└── Database queries
