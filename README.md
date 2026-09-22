<div align="center">

# 📚 Bookshop Management System

### A Microsoft Access-Based Database Solution for Book Shop Management

[![Microsoft Access](https://img.shields.io/badge/Microsoft%20Access-A4373A?style=for-the-badge&logo=microsoftaccess&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/access)
[![Database](https://img.shields.io/badge/Database-MS%20Access%20(.accdb)-0078D4?style=for-the-badge)](https://support.microsoft.com/en-us/office/basic-tasks-for-a-database-9c2f1e34-7a52-4b1b-9e7a-8c1b1e8e5e0a)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](CONTRIBUTING.md)

**A complete Microsoft Access database application** designed to manage book shop operations — including book inventory, customer records, sales transactions, supplier management, and employee details — all through an intuitive Access interface.

[📥 Download](#-getting-started) · [🐛 Report Bug](https://github.com/SIRATHNAYAKA/Bookshop-Management-System/issues) · [✨ Request Feature](https://github.com/SIRATHNAYAKA/Bookshop-Management-System/issues)

</div>

---

## 📑 Table of Contents

<details open>
<summary>Click to expand / collapse</summary>

- [📌 Overview](#-overview)
- [🎯 Key Highlights](#-key-highlights)
- [✨ Features](#-features)
- [🛠 Tech Stack](#-tech-stack)
- [🏗 Database Architecture](#-database-architecture)
- [📂 Project Structure](#-project-structure)
- [🗄 Database Schema](#-database-schema)
- [🚀 Getting Started](#-getting-started)
- [🎮 Usage](#-usage)
- [🖼 Screenshots](#-screenshots)
- [🔐 Security Notes](#-security-notes)
- [🔮 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [📬 Contact](#-contact)

</details>

---

## 📌 Overview

**Bookshop Management System** is a comprehensive **Microsoft Access** database application built for book shops and bookstores. It digitizes and streamlines the traditionally manual, paper-based processes of book inventory management, sales tracking, customer management, supplier records, and employee administration.

The system provides a single, centralized database where book shop owners and staff can:

- **Manage book inventory** — add, edit, search, and track stock levels of books
- **Process sales** — generate bills, apply discounts, and record transactions
- **Track customers** — maintain customer records and purchase history
- **Manage suppliers** — record supplier details and purchase orders
- **Handle employees** — store employee information and work records
- **Generate reports** — sales summaries, stock reports, customer lists, and more

Built entirely in **Microsoft Access**, this solution is lightweight, portable, and requires no additional software installation beyond Microsoft Access or the free Access Runtime.

> 💡 **Why this project?** Small book shops often struggle with manual inventory tracking and sales recording. This Access-based system provides an affordable, instantly deployable digital solution that requires zero programming knowledge to operate — ideal for small to medium-sized book shops.

---

## 🎯 Key Highlights

| 🏆 | Highlight |
| :-: | :--- |
| 📖 | **Complete book inventory** — title, author, ISBN, category, price, stock |
| 💰 | **Sales & billing** — generate bills, apply discounts, record payments |
| 👥 | **Customer management** — customer records with purchase history |
| 🏭 | **Supplier management** — supplier details and purchase tracking |
| 👔 | **Employee records** — staff information and roles |
| 📊 | **Built-in reports** — sales reports, stock reports, customer lists |
| 🔍 | **Search & filter** — quickly find books by title, author, or category |
| 📋 | **Data validation** — input masks and validation rules prevent errors |
| 🔒 | **Access security** — password-protected database |
| 📱 | **Portable** — single `.accdb` file, easily backed up and transferred |

---

## ✨ Features

### 📚 Book Inventory Management

| Feature | Description |
| :--- | :--- |
| ➕ **Add New Book** | Register new books with title, author, ISBN, category, price, and stock quantity |
| ✏️ **Edit Book Details** | Update price, stock, or other details anytime |
| 🔍 **Search Books** | Find by title, author, ISBN, or category |
| 📋 **Book List** | View all books in a sortable, filterable table |
| 🗑️ **Delete Book** | Remove discontinued or out-of-print books |
| 📊 **Stock Tracking** | Monitor current stock levels and low-stock alerts |

### 🛒 Sales & Billing

| Feature | Description |
| :--- | :--- |
| 🧾 **Generate Bill** | Create customer bills with multiple books |
| 💰 **Apply Discounts** | Apply percentage or fixed discounts on sales |
| 📝 **Record Payment** | Track payment method (cash, card, etc.) |
| 📜 **Sales History** | View all past transactions with details |
| 🔎 **Search Sales** | Find sales by date, customer, or bill number |
| 🖨️ **Print Receipt** | Generate printable customer receipts |

### 👥 Customer Management

| Feature | Description |
| :--- | :--- |
| ➕ **Add Customer** | Register new customers with contact details |
| ✏️ **Edit Customer** | Update customer information |
| 📋 **Customer List** | View all registered customers |
| 📊 **Purchase History** | See all purchases made by a customer |
| 🔍 **Search Customer** | Find by name, phone, or email |

### 🏭 Supplier Management

| Feature | Description |
| :--- | :--- |
| ➕ **Add Supplier** | Register new book suppliers with contact details |
| ✏️ **Edit Supplier** | Update supplier information |
| 📋 **Supplier List** | View all suppliers |
| 📦 **Purchase Orders** | Record purchases from suppliers |
| 📊 **Supplier History** | Track purchase history per supplier |

### 👔 Employee Management

| Feature | Description |
| :--- | :--- |
| ➕ **Add Employee** | Register employees with personal and role details |
| ✏️ **Edit Employee** | Update employee information |
| 📋 **Employee List** | View all employees |
| 🎯 **Designation** | Assign roles (Manager, Cashier, Stock Keeper, etc.) |

### 📊 Reports & Analytics

| Report | Description |
| :--- | :--- |
| 📋 **Book List Report** | Complete inventory with stock levels and values |
| 💰 **Sales Report** | Daily/monthly sales summaries with revenue |
| 👥 **Customer List** | All customers with contact details |
| 🧾 **Bill / Receipt** | Individual transaction receipt |
| 📦 **Stock Report** | Low-stock and out-of-stock books |
| 🏭 **Supplier Report** | Supplier contact list and purchase history |
| 📈 **Profit Report** | Revenue vs. cost analysis |

---

## 🛠 Tech Stack

<div align="center">

| Category | Technology |
| :--- | :--- |
| **Platform** | Microsoft Access (2016 / 2019 / 2021 / 365) |
| **Database File** | `.accdb` (Access Database) |
| **Interface** | Access Forms (Navigation Forms, Data Forms, Dialog Forms) |
| **Reports** | Access Reports (with grouping, sorting, and calculations) |
| **Queries** | Access Queries (Select, Action, Crosstab, Parameter) |
| **Macros / VBA** | Microsoft Visual Basic for Applications (VBA) |
| **Security** | Database password protection |
| **Runtime** | Microsoft Access Runtime (free) for deployment |

</div>

> **Note:** No external libraries, APIs, or internet connection required. Everything runs locally within Microsoft Access.

---

## 🏗 Database Architecture

The system follows a **relational database design** normalized to **Third Normal Form (3NF)** to eliminate data redundancy and ensure integrity.
