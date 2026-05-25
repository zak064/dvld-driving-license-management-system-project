<div align="center">

# 🚗 DVLD – Driving License Management System

### A desktop application for managing driving license services.

<p>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" />
  <img src="https://img.shields.io/badge/.NET_Framework-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/WinForms-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/ADO.NET-6A1B9A?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/OOP-0A66C2?style=for-the-badge&logo=codeforces&logoColor=white" />
  <img src="https://img.shields.io/badge/3--Tier_Architecture-FF9800?style=for-the-badge&logo=dependabot&logoColor=white" />
</p>

<p>
  A full desktop management system built with <strong>C#</strong>, <strong>WinForms</strong>, <strong>SQL Server</strong>, and <strong>ADO.NET</strong>.
</p>

</div>

---

## 📌 Project Overview

**DVLD** stands for **Driving & Vehicle License Department**.

This project simulates a real driving license department system. It helps manage the full workflow of driving license services, from registering people and applications to scheduling tests, issuing licenses, renewing licenses, and handling detained licenses.

The system is designed to manage:

- People
- Users
- Drivers
- Driving license applications
- Tests and appointments
- Local licenses
- International licenses
- License renewals
- Replacement licenses
- Detained licenses

---

## 🚀 Features

- 👤 People management
- 👥 User management
- 🔐 Login system
- 🚗 Driver management
- 📄 Local driving license applications
- 🪪 License classes management
- 📋 Application types management
- 🧪 Test types and appointments
- ✅ Test result handling
- 🌍 International license issuing
- 🔄 License renewal
- 🛠️ Replacement for lost or damaged licenses
- ⛔ Detained licenses management
- 💰 Fine payment and detained license release
- 🔍 Search and filtering
- ✔️ Data validation
- 🖼️ Image handling
- 🧩 User controls
- 🧠 Business rules validation

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
- Track the current logged-in user

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

<div align="center">

| Technology | Description |
|------------|-------------|
| **C#** | Main programming language |
| **.NET Framework** | Application framework |
| **Windows Forms** | Desktop user interface |
| **SQL Server** | Database management system |
| **ADO.NET** | Database connectivity |
| **OOP** | Object-oriented programming principles |
| **3-Tier Architecture** | Separation of Presentation, Business, and Data Access layers |
| **SQL Queries** | Data retrieval and database operations |
| **User Controls** | Reusable WinForms UI components |
| **Delegates & Events** | Communication and event-driven programming |

</div>

---

## 🏗️ Architecture

The project follows **3-Tier Architecture**:

```text
Presentation Layer
│
├── Windows Forms UI
├── User Controls
├── Validation
└── User Interaction

Business Layer
│
├── Business Rules
├── Application Logic
├── Validation Logic
└── Object-Oriented Classes

Data Access Layer
│
├── SQL Server Connection
├── CRUD Operations
├── ADO.NET
└── Database Queries
