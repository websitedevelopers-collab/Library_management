## Library Management System SQL Project
This project is a Library Management System developed using PostgreSql. It provides a robust relational database schema designed to handle essential library operations, including managing books, employees, members, book issuance, returns, and tracking library performance. The system is structured with clear entity relationships and is easily extendable for new features.

## ERD (Entity Relationship Diagram)
The project includes a comprehensive Entity Relationship Diagram (ERD) showcasing relationships between core entities:
-Books
-Branches
-Employees
-Members
-Issued Status
-Return Status
![WhatsApp Image 2025-07-25 at 13 53 57_1243f108](https://github.com/user-attachments/assets/94662308-9b9d-41d3-a618-1e45c71b7b2e)


## Project Description
Branches: Manage library locations, including address, manager, and contact info.
Books: Store details like ISBN, title, category, status, rental price, author, and publisher.
Employees: Keep records of staff, including their positions, salaries, and associated branch.
Members: Manage member registration, addresses, and history of borrowings.
Issued Status / Return Status: Track which books are issued to which members by which employees, and when the books are returned.
Reports: Generate analytical tables for active members, book issue counts, branch performance, and high-rental books.

## Features
Add, update, or delete books, members, and employees.
Issue and return books with full status tracking.
Generate statistical reports (e.g., most active members, overdue books, branch performance).
Maintain integrity with foreign key constraints and normalized tables.

## Prerequisites
PostgreSQL (or compatible SQL database)
SQL client tools (e.g., pgAdmin or command-line psql)

## Setup Instructions

# 1. Clone the Repository
git clone https://github.com/your-username/library-management-sql.git
cd library-management-sql





