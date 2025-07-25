## Library Management System SQL Project
This project is a Library Management System developed using PostgreSql. It provides a robust relational database schema designed to handle essential library operations, including managing books, employees, members, book issuance, returns, and tracking library performance. The system is structured with clear entity relationships and is easily extendable for new features.

## ERD (Entity Relationship Diagram)
The project includes a comprehensive Entity Relationship Diagram (ERD) showcasing relationships between core entities:
- Books
- Branches
- Employees
- Members
- Issued Status
- Return Status
  <img width="1181" height="834" alt="image" src="https://github.com/user-attachments/assets/f07b1564-adf7-426e-8721-15da4183125d" />

### 🧱 Key Components

* **Books**: Stores ISBN, title, category, rental price, author, publisher, and availability.
* **Branches**: Tracks locations, contact details, and branch managers.
* **Employees**: Records staff details with positions, salaries, and assigned branches.
* **Members**: Contains personal info, registration, and borrowing history.
* **Issued/Return Status**: Logs book issuance and return records with timestamps.
* **Reports**: Helps generate views for analytics like top books, active members, and branch-wise performance.
  

## Features
* Add, update, or delete books, members, and employees.
* Issue and return books with full status tracking.
* Generate statistical reports (e.g., most active members, overdue books, branch performance).
* Maintain integrity with foreign key constraints and normalized tables.

---

### 📦 Files Included

* `project1.sql` – Main schema and table creation
* `Riyasql.sql` – Sample data inserts
* `README.md` – Documentation
* `ERD.png` – Entity Relationship Diagram (optional but recommended)

---

## 🚀 Uploading to GitHub – Step-by-Step

Follow these steps to upload your project to GitHub:

### ✅ Step 1: Prepare Your Folder

```
/Library-Management-SQL
    ├── project1.sql
    ├── Riyasql.sql
    ├── README.md
    └── ERD.png
```

### ✅ Step 2: Initialize Git

Open **Git Bash** or **Command Prompt** in that folder and run:

```bash
git init
```

This will initialize the folder as a Git repository.

---

### ✅ Step 3: Add Files to Git

```bash
git add .
```

This adds all the files to the staging area.

---

### ✅ Step 4: Commit Your Changes

```bash
git commit -m "Initial commit: Library Management System SQL project"
```

---

### ✅ Step 5: Create a GitHub Repository

1. Go to [https://github.com](https://github.com)
2. Click on **New Repository**
3. Name it something like `library-management-sql`
4. **DO NOT** initialize with README or .gitignore if you already have them
5. Click **Create repository**

---

### ✅ Step 6: Link Local Project to GitHub

Copy the remote URL from GitHub (e.g., `https://github.com/your-username/library-management-sql.git`) and run:

```bash
git remote add origin https://github.com/your-username/library-management-sql.git
git branch -M main
```

### ✅ Step 7: Push to GitHub

```bash
git push -u origin main
```

Enter your GitHub credentials or token if prompted. After this, your project will be live on GitHub!

---


## ✅ Final Result

Your SQL project is now successfully uploaded to GitHub. You (or anyone else) can now:

* Clone it
* Execute the SQL scripts
* Review the schema with the ERD
* Extend the database with new features

## Prerequisites
PostgreSQL (or compatible SQL database)
SQL client tools (e.g., pgAdmin or command-line psql)






