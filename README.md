# 🧩 Customer Management System (PHP CRUD)

> A simple yet powerful **Customer Management System** built with pure PHP and MySQL.  
> Designed to help small teams easily **create, view, edit, and delete** customer records — no heavy frameworks required.

## 📋 Overview

This project is a **CRUD-based web application** for managing customer data.  
It allows users to add, edit, view, and delete clients in a clean and minimal interface.

### ✨ Features
- ➕ Add new customer  
- 📝 Edit existing customer details  
- 🔍 View customer list  
- ❌ Delete customer record  
- 💾 Data stored securely in MySQL  
- 🧭 Simple and responsive UI (Bootstrap ready)

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-------------|
| Backend | PHP (Procedural or OOP style) |
| Database | MySQL |
| Frontend | HTML, CSS, JavaScript |
| UI Framework | Bootstrap 5 |
| Server | Apache / XAMPP / Laragon |

---

## ⚙️ Installation

```bash
# 1 Move the folder into your XAMPP or Laragon www directory
# Example:
C:\xampp\htdocs\customer-management-php

# 2 Create a MySQL database
# Example database name: crm_db

# 3 Import the SQL file (database.sql) located in the project folder

# 4 Configure the connection in config.php
$host = "localhost";
$user = "root";
$password = "";
$dbname = "crm_db";

# 5 Run the project
Open http://localhost/customer-management-php in your browser
