# 📦 OpenStock

> **OpenStock: Web-Based Inventory Monitoring System with Real-Time Department Status**  
> *Developed for Luis Y. Ferrer Jr. Senior High School*

[![Status](https://img.shields.io/badge/Status-Active%20Development-brightgreen)](#)
[![License](https://img.shields.io/badge/License-MIT-blue)](#)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile--Responsive-orange)](#)
[![Evaluation](https://img.shields.io/badge/Evaluation-ISO%2FIEC%2025010-purple)](#)

---

## 📌 Overview

**OpenStock** is a centralized, mobile-responsive web platform designed to streamline material resource management and provide real-time facility visibility across Luis Y. Ferrer Jr. Senior High School. 

The system unifies two traditionally disconnected campus workflows:
1. **Supply Inventory Tracking:** Stock levels, threshold warnings, batch updates, and automated depletion alerts.
2. **Real-Time Department Status:** Instant visibility into whether a room is open, closed, or unattended before visiting.

---

## 🎯 Target Departments

- 🏥 **School Clinic:** First-aid kits, OTC medicines, and emergency medical supplies
- 📚 **School Library:** Reference books, learning modules, and physical media
- 🗄️ **Central Stock Room:** Office supplies, paper reams, printing consumables, and cleaning supplies
- 💻 **Computer Laboratories:** PC peripherals, network cables, adapters, and hardware maintenance tools

---

## ✨ Key Features

### 🟢 Real-Time Department Status & Presence Indicator
- One-click status toggle for assigned coordinators:
  - 🟢 **Open / Available**
  - 🟡 **Temporarily Away / In Session**
  - 🔴 **Closed / Off-Duty**
- Eliminates unnecessary trips across campus, preserving instructional time for students and teachers.

### 📊 Decentralized Inventory Management
- Dedicated supply catalog per department with item categorization, serial numbers, and unit measurements.
- Real-time stock counters updating immediately upon item issuance or replenishment.
- **Low-Stock Triggers:** Visual alerts flag items approaching critical depletion levels.

### 📝 Immutable Audit Trail & Accountability
- Automatically logs user identity, date, timestamp, and action type (In / Out / Adjusted) for every transaction.
- Eliminates untraceable record discrepancies and enforces custodian accountability.

### 📱 Responsive Public Viewer Dashboard
- Accessible on desktop and mobile browsers without requiring login credentials.
- Students and teachers can search for supplies or check room availability on the fly.

### 📈 Administrative Reporting & Export
- Generates periodic inventory summaries and movement logs for administration and procurement reviews.

---

## 👥 User Roles & Permissions

| Role | Target Users | Access Scope |
| :--- | :--- | :--- |
| **Viewer** | Students, Faculty, Parents | View department open/closed status, search consumable item availability. |
| **Coordinator** | Clinic Staff, Librarian, Lab Custodians | Manage departmental stock, update room status, log supply intake/dispatch. |
| **Administrator** | Principal, Assistant Principal, ICT Head | Master view across all departments, user role management, system-wide export reports. |

---

## 🛠️ Technology Stack

- **Frontend:** HTML5, CSS3 / Tailwind CSS, JavaScript (ES6+)
- **Backend & API:** Google Apps Script Web App *(or Node.js / Express)*
- **Database:** Google Sheets API *(or Supabase / PostgreSQL)*
- **Deployment & Hosting:** Netlify / Vercel / GitHub Pages
- **Version Control:** Git & GitHub

---

## 🧪 Evaluation Framework

This system is formally assessed in accordance with the **ISO/IEC 25010 Software Quality Standards**:
1. **Functional Suitability:** Completeness and correctness of stock logging and room status toggling.
2. **Performance Efficiency:** Response latency during live status updates and search queries.
3. **Usability:** Interface navigation clarity, color-coded accessibility, and mobile layout.
4. **Reliability:** Data consistency across concurrent user sessions.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🏫 Institutional Attribution

**Luis Y. Ferrer Jr. Senior High School**  
Senior High School Department — Technical-Vocational-Livelihood (TVL) / ICT Track
