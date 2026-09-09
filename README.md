# Medical Diagnostic Center – ServiceNow

![Platform](https://img.shields.io/badge/PLATFORM-ServiceNow-81B5A1?style=flat-square)
![Application](https://img.shields.io/badge/APPLICATION-Medical%20Diagnostics-00A878?style=flat-square)
![Scope](https://img.shields.io/badge/SCOPE-Private%20Scope-4CAF50?style=flat-square)
![Security](https://img.shields.io/badge/SECURITY-Role%20Based-2196F3?style=flat-square)
![Automation](https://img.shields.io/badge/AUTOMATION-Workflow-FF9800?style=flat-square)
![Frontend](https://img.shields.io/badge/FRONTEND-Service%20Portal-00A9CE?style=flat-square)
![Status](https://img.shields.io/badge/PROJECT-COMPLETED-4CAF00?style=flat-square)

---

## 🏥 Project Overview

The **Medical Diagnostic Center** is a ServiceNow-based application designed to manage the complete workflow of medical diagnostic tests — from test selection and appointment booking to administrator approval, test completion, email notifications, and report generation.

The application combines **ServiceNow backend development, workflow automation, data management, and frontend development** to provide a structured diagnostic test management system.

---

## ✨ Key Features

- 🧪 Diagnostic test catalog
- 🔎 Test search and category filtering
- 📅 Patient appointment booking
- ✅ Administrator approval workflow
- 🔄 Appointment status management
- 📧 Automated email notifications
- 📄 Lab report generation
- 👤 Patient-specific records
- 🔐 Role-based access control
- 🎨 Custom Service Portal interface

---

## 🏗️ Core Architecture

| Table | Purpose |
|---|---|
| 🧪 **Diagnostic Test** | Maintains all available diagnostic tests, including category, price, duration, description, and availability. |
| 📅 **Appointment** | Stores patient booking information and manages the appointment workflow. |
| 📄 **Report** | Stores generated reports for completed diagnostic tests. |
| 👤 **Patient** | Maintains unique patient information associated with users. |

---

## 🔄 Project Workflow

```text
Patient
   │
   ▼
Browse Diagnostic Tests
   │
   ▼
Book Test
   │
   ▼
Appointment Created
   │
   ▼
Administrator Approval
   │
   ▼
Test Completed
   │
   ▼
Report Generated
   │
   ▼
Patient Views Report
