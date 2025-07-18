
# 🏦 Bank Management System – SQL Database Project

## 📌 Overview
This project is a **Bank Management System** implemented in SQL. It manages critical banking entities such as branches, employees, customers, accounts, loans, and transactions. The system is designed to simulate real-world banking operations using a relational database model.

## 🛠️ Technologies Used
- **Database:** MySQL
- **Scripts:** SQL (DDL & DML)
- **Diagrams:** ER Diagram and Schema PNGs included

## 🗃️ Database Design

The database consists of the following main tables:

- `Branch` – Stores branch-level data
- `Employee` – Linked to a branch via foreign key
- `Customer` – Each customer is registered with a specific branch
- `AccountType` and `Account` – Tracks customer accounts
- `TransactionType` and `Transaction` – Handles deposits, withdrawals, etc.
- `LoanType`, `Loan`, and `LoanRepayment` – Manages loans and repayments

🖼️ ER Diagram:  
![ER Diagram](ER-%20DBPROJECT.png)

🗺️ Schema Diagram:  
![Schema](DB%20Project%20Schema.png)

## 🔑 Key Features
- Schema creation using `CREATE TABLE` with primary and foreign key constraints
- Support for various account and loan types
- Transaction logging with descriptions and timestamps
- Entity relationships reflect realistic banking scenarios

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/bank-management-system.git
