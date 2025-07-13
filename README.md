<h1 align="center">📊 Celebal SQL Internship Tasks - Summer 2025 </h1>

Welcome to the official repository for my SQL tasks completed during the **Celebal Technologies Summer Internship 2025**. This repository is structured week-wise as per the course modules provided on the Celebal Internship Portal.

---

## 📅 Internship Details

- **🏢 Company:** Celebal Technologies  
- **👨‍💻 Role:** SQL Intern  
- **📆 Duration:** June 2, 2025 – August 3, 2025  

---

## 🗂 Weekly Breakdown

### 🔹 Week 1 - DDL & Basic SQL Operations
Tasks focused on foundational SQL concepts like:

- Creating, Altering, Dropping Databases and Tables  
- SQL Constraints (Primary, Foreign, Default, Check, etc.)  
- Data Types in SQL Server  
- SQL Commands: `INSERT`, `UPDATE`, `DELETE`  
- `SELECT` Statements  
- Joins and Advanced Joins  
- Aggregation and Set Operations  
- Relationship Modeling and Referential Integrity  

📁 **Folder:** `Week-1-DDL/`  
📄 **Assignment:** `Level A Task Solutions`

---

### 🔹 Week 2 - Built-In Functions, Procedures, Views & Triggers

This week focuses on advanced SQL concepts using the **AdventureWorks2022** database, including built-in functions, user-defined functions, stored procedures, views, and triggers.

#### 📚 Key Topics:

- Built-in String, DateTime, Math, Cast/Convert Functions  
- User Defined Functions (UDFs)  
- Views (Standard, Updatable, Indexed, with Limitations)  
- Stored Procedures for Insert, Update, Delete, Fetch Operations  
- Triggers for Referential Integrity and Inventory Management  

📁 **Folder:** `Week-2-BuiltIn-Functions/`  
📄 **Assignment:** `Level B Task Solutions`

---

### 🔹 Week 3 - Indexes, Stored Procedures & Subqueries

This week dives into **performance optimization** and **modular SQL programming** through indexes, stored procedures, and subqueries.

#### 📚 Key Topics:

- Temporary Tables  
- Indexes (Part 1 & 2)  
- Unique vs Non-Unique Indexes  
- Pros and Cons of Indexes  
- Stored Procedures  
- Stored Procedures with Output Parameters (Part 1 & 2)  
- Advantages of Stored Procedures  
- Subqueries & Correlated Subqueries  
- Performance Comparison: Subquery vs Join  

📁 **Folder:** `Week-3-Indexes/`  
📄 **Assignment:** `Level C Task Solutions`

---
### 🔹 Week 4 - Triggers & Student Allotment Logic

This week focuses on **DML triggers** and their practical use cases, including conditional logic during `INSERT`, `UPDATE`, and `DELETE` operations. The week concludes with a subject allotment assignment based on GPA and preference order.

#### 📚 Key Topics:

- DML Triggers  
- AFTER UPDATE Trigger  
- INSTEAD OF INSERT Trigger  
- INSTEAD OF UPDATE Trigger  
- INSTEAD OF DELETE Trigger  

📁 **Folder:** `Week-4-Triggers/`  
📄 **Assignment:** `Student Allotment SQL Problem`  
📝 **Summary:** Students are allotted elective subjects based on their GPA and preference priority. A stored procedure processes preferences in order and marks unallotted students if no seat is available.

---

### 🔹 Week 5 - Common Table Expressions (CTE)

This week covers **Common Table Expressions (CTE)** and their use in modular query writing. Topics include recursive CTEs, updatable CTEs, and using them in practical scenarios. The assignment implements a subject change request tracker using stored procedures.

#### 📚 Key Topics:

- Common Table Expressions (CTE) – Part 1 & 2  
- Updatable CTEs  
- Recursive CTE  

📁 **Folder:** `Week-5-CTE/`  
📄 **Assignment:** `Subject Change Request Problem`  
📝 **Summary:** A stored procedure checks if the student's requested subject is different from the currently active subject. It updates the current subject’s status and inserts the new one as valid, preserving the history of allotments.

---

### 🔹 Week 6 - Pivot, Error Handling, Transactions & LeetCode Problems

This week introduces **data reshaping**, **robust error handling**, and **transaction management** in SQL Server. It also includes **LeetCode-style SQL problems** that help apply concepts in real-world scenarios.

#### 📚 Key Topics:

- `PIVOT` – Transform rows into columns  
- `UNPIVOT` – Transform columns back into rows  
- Error Handling using `TRY...CATCH` blocks  
  - Error Handling – Part 1: Handling syntax/logical errors  
  - Error Handling – Part 2: Custom error messages, nested try-catch  
- Transactions & ACID Properties  
- `MERGE` Statement – Conditional `INSERT`, `UPDATE`, or `DELETE`  
- **Window Functions**:  
  - `ROW_NUMBER()`  
  - `RANK()`  
  - `DENSE_RANK()`  
  - `NTILE()`  
- LeetCode SQL Problems (Performance-focused)

📁 **Folder:** `Week-6-Pivot/`  
📄 **Assignment:** `Perform  Leetcode Questions`

---

## 🚀 How to Use

1. Clone this repository or download it as a ZIP.  
2. Open `.sql` files using SQL Server Management Studio (SSMS) or Mysql WorkBench 8.0
3. Execute the queries on the **Adventure works2022** database.  
4. Files are named and commented for clarity.

---

## 👤 Author

**Krishna Shelar**  
💼 SQL Intern @ Celebal Technologies  
🔗 [LinkedIn](https://www.linkedin.com/in/krishna-shelar-75294a255/)  

---

> 📌 _This repository will be updated weekly with new assignments and tasks._
