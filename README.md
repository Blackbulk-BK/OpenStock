# 📦 OpenStock
### Web-Based Inventory Monitoring System with Real-Time Department Status

**Concept by:** Henrich G. Angeles  
**Prepared by:** Henrich G. Angeles

**Developed for Luis Y. Ferrer Jr. Senior High School**

[![Status](https://img.shields.io/badge/Status-Active%20Development-brightgreen)](#project-status)
[![License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile--Responsive-orange)](#technology-stack)
[![Quality Standard](https://img.shields.io/badge/Quality%20Standard-ISO%2FIEC%2025010-purple)](#software-quality-evaluation)

---

## 📌 About the Project

**OpenStock** is a web-based, mobile-responsive inventory monitoring system designed to improve supply management, resource tracking, and department availability monitoring at **Luis Y. Ferrer Jr. Senior High School**.

The system provides a centralized platform where authorized personnel can manage departmental inventory, monitor stock levels, record supply transactions, and update department availability. Students and teachers can check department status and search for available supplies through a public-facing dashboard.

By digitizing inventory records and making department information accessible, OpenStock aims to reduce manual recordkeeping, improve accountability, and minimize unnecessary trips between school facilities.

### 🎯 Project Objectives

- Centralize inventory records across participating school departments.
- Provide timely updates on stock levels and department availability.
- Improve accountability through transaction logs and activity records.
- Help students and faculty locate supplies efficiently.
- Generate inventory reports to support administrative planning and procurement.
- Provide an accessible interface for desktop and mobile devices.

---

## 🏫 Target Departments

| Department | Inventory Examples |
|---|---|
| 🏥 **School Clinic** | First-aid supplies, over-the-counter medicines, and emergency materials |
| 📚 **School Library** | Reference books, learning modules, and educational media |
| 🗄️ **Central Stock Room** | Office supplies, bond paper, printing materials, and cleaning supplies |
| 💻 **Computer Laboratories** | Computer peripherals, network cables, adapters, and maintenance tools |

*Participating departments and inventory categories may be adjusted according to the school's requirements.*

---

## ✨ Key Features

### 🟢 1. Real-Time Department Status

Check the latest recorded availability of participating school departments through a color-coded status indicator.

- 🟢 **Open / Available** — The department is available according to its assigned coordinator.
- 🟡 **Temporarily Away / In Session** — The coordinator is temporarily unavailable or the department is occupied.
- 🔴 **Closed / Off-Duty** — The department is currently unavailable.

Authorized coordinators can update their department's status, allowing students and teachers to check availability before visiting.

### 📦 2. Department-Based Inventory Management

Each participating department has its own inventory catalog.

- Add, edit, and organize inventory items.
- Categorize supplies for easier searching.
- Record quantities, units of measurement, and relevant identifiers.
- Monitor current stock levels.
- Record incoming supplies and outgoing items.
- Maintain separate inventory records for each department.

### ⚠️ 3. Low-Stock Alerts

Help prevent unexpected shortages with configurable minimum-stock thresholds.

- Identify items that have reached or fallen below their minimum stock level.
- Highlight supplies that require replenishment.
- Support informed purchasing and restocking decisions.

### 📝 4. Inventory Transaction Logs

Maintain records of inventory movements to improve transparency and accountability.

Transaction records can include:

- Item and department
- Transaction type: Stock In, Stock Out, or Adjustment
- Quantity involved
- Date and time
- User responsible for the transaction
- Optional notes or explanations

Transaction records should be protected against unauthorized modification or deletion. Strictly immutable logs require additional database permissions and audit controls.

### 🔎 5. Public Viewer Dashboard

Provide students and faculty with convenient access to permitted inventory and department information.

- View department availability.
- Search for specific supplies.
- Check recorded stock quantities and availability.
- Navigate a mobile-friendly interface.
- Access public information without creating an account.

Sensitive administrative information and restricted operations remain accessible only to authorized users.

### 📊 6. Administrative Reports

Help administrators review inventory activity and prepare for future supply requirements.

- Generate inventory summaries.
- Review stock-in and stock-out transactions.
- Identify low-stock and depleted items.
- Filter records by department, item, or date range.
- Export reports for administrative review and procurement planning.

### 🔐 7. Role-Based Access Control

Restrict system functions according to each user's assigned role.

- **Viewer:** View permitted department status and inventory information.
- **Coordinator:** Manage assigned department inventory, update department status, and record transactions.
- **Administrator:** Oversee participating departments, manage user roles, and access authorized system-wide reports.

Restricted operations must be validated by the backend, not merely hidden from the user interface.

---

## 👥 User Roles and Permissions

| Role | Intended Users | Permissions |
|---|---|---|
| **Viewer** | Students, faculty, and permitted visitors | View department status and search publicly available inventory information. |
| **Coordinator** | Clinic personnel, librarian, laboratory custodian, and stockroom personnel | Manage assigned department inventory, update status, and record supply movements. |
| **Administrator** | Authorized school administrators and ICT personnel | Manage users and roles, oversee departments, and generate system-wide reports. |

*Permissions should be configured according to school policies and the responsibilities assigned to each user.*

---

## 🛠️ Technology Stack

OpenStock can be implemented using the following technologies, depending on the final system architecture.

| Component | Proposed Technologies |
|---|---|
| **Frontend** | HTML5, CSS3, JavaScript (ES6+) |
| **UI Framework** | Tailwind CSS (optional) |
| **Backend / API** | Google Apps Script or Node.js with Express |
| **Database** | Google Sheets or Supabase with PostgreSQL |
| **Deployment** | Netlify, Vercel, or another compatible hosting platform |
| **Version Control** | Git and GitHub |

**Implementation note:** These are proposed technology options. The selected backend and database must be configured to work together.

For example, Google Apps Script can communicate with Google Sheets, while a Node.js application can use PostgreSQL through Supabase.

---

## 🔄 How OpenStock Works

1. **Access the dashboard:** View department status and search for available supplies.
2. **Select a department:** Review inventory information permitted for that department.
3. **Manage supplies:** Authorized coordinators record incoming stock, outgoing items, and inventory adjustments.
4. **Update department status:** Coordinators publish the latest availability information.
5. **Monitor stock levels:** The system identifies items that require replenishment.
6. **Generate reports:** Administrators review inventory activity and export relevant records.

---

## 🧪 Software Quality Evaluation

OpenStock is intended to be evaluated using relevant characteristics of **ISO/IEC 25010**, a software product quality model.

| Quality Characteristic | Evaluation Focus |
|---|---|
| **Functional Suitability** | Correctness and completeness of inventory management, transaction logging, and status updates |
| **Performance Efficiency** | Response time for searches, inventory operations, and department status updates |
| **Usability** | Navigation clarity, interface consistency, accessibility, and mobile responsiveness |
| **Reliability** | Data consistency, error handling, and recovery from failed operations |
| **Security** | Authentication, role-based authorization, and protection against unauthorized access |
| **Maintainability** | Code organization, modularity, and ease of fixing or extending the system |

Evaluation should use defined test cases, user feedback, and measurable results. Referencing ISO/IEC 25010 does not by itself constitute formal certification.

---

## 🔒 Security and Data Integrity

Because OpenStock handles school inventory records and user accounts, the implementation should include appropriate safeguards.

- Authenticate users accessing restricted functions.
- Enforce role-based authorization on the backend.
- Validate submitted data before saving transactions.
- Prevent unauthorized changes to inventory records.
- Protect administrative accounts and configuration settings.
- Maintain reliable backups and recovery procedures.
- Avoid exposing private information on the public dashboard.

---

## 🚀 Project Status

**Current Status:** Active Development

OpenStock is under development as a school inventory and department-status management platform. Feature availability depends on the current implementation.

### Development Checklist

- [ ] Department inventory management
- [ ] Department status monitoring
- [ ] User authentication and role-based permissions
- [ ] Stock-in, stock-out, and adjustment records
- [ ] Low-stock indicators
- [ ] Searchable public dashboard
- [ ] Administrative reports and data export
- [ ] Mobile-responsive interface
- [ ] Functional testing and user evaluation

*Update this checklist as each feature is implemented and tested.*

---

## 📂 Suggested Project Structure

```text
OpenStock/
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
├── pages/
│   ├── dashboard.html
│   ├── inventory.html
│   ├── departments.html
│   └── reports.html
├── README.md
├── LICENSE
└── .gitignore
```

*This is a suggested structure. Adjust it to match the actual project files and framework.*

---

## 🤝 Development and Contributions

OpenStock aims to support more organized and transparent school resource management.

During development, bug reports and proposed improvements can be documented through GitHub Issues or discussed with the project maintainer. Contributions should follow the project's coding conventions and protect confidential school information.

---

## 📄 License

This project is intended to be distributed under the **MIT License**.

See the [`LICENSE`](LICENSE) file for the complete license terms. Ensure the repository contains the appropriate license file before claiming the project is officially licensed under MIT.

---

## 🏫 Institutional Attribution

**Luis Y. Ferrer Jr. Senior High School**  
Senior High School Department  
Technical-Vocational-Livelihood (TVL) / Information and Communications Technology (ICT) Track

---

<p align="center">
  <strong>OpenStock</strong><br>
  Making school inventory more organized, accessible, and accountable.
  <br><br>
  Concept by <strong>Henrich G. Angeles</strong><br>
  Prepared by <strong>Henrich G. Angeles</strong>
</p>
