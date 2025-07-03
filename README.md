# Employee-Database-App
# 💼 Java JDBC – Employee Database App

This Java console application connects to a **MySQL database** and performs **CRUD operations** on an employee table using **JDBC** and **PreparedStatements**.

---

## 🧠 Features

- Add new employee
- View all employees
- Update employee designation
- Delete employee by ID
- JDBC-based secure connection using PreparedStatement

---

## 🧰 Tech Stack

- Java (JDK 8+)
- MySQL 5.7+ / 8.0
- JDBC
- VS Code / IntelliJ / Eclipse

---

## 🛠️ Setup Instructions

1. Import the JDBC driver `.jar` (e.g., `mysql-connector-java-x.x.x.jar`)
2. Create DB and table in MySQL:
```sql
CREATE DATABASE employeedb;
USE employeedb;
CREATE TABLE employees (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    designation VARCHAR(100)
);
