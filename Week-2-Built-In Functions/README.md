# Week 2 - Built-In Functions, Stored Procedures, Views, and Triggers

Welcome to Week 2 of the SQL Internship at Celebal Technologies!  
This week covers advanced SQL features such as built-in functions, user-defined functions, stored procedures, views, and triggers using the AdventureWorks database.

---

### 📘 Topics Covered

- ✅ Built-in String Functions  
- ✅ DateTime Functions  
- ✅ Cast and Convert Functions  
- ✅ Mathematical Functions  
- ✅ User Defined Functions (UDF) – Scalar Functions  
- ✅ Views in SQL Server  
- ✅ Updatable Views  
- ✅ Indexed Views  
- ✅ View Limitations  
- ✅ Stored Procedures  
- ✅ Triggers  

---

### 📂 Assignment - Level B Task

Below is the list of tasks to be completed using the AdventureWorks database:

#### 🔁 Stored Procedures

1. **InsertOrderDetails**:  
   - Inserts order details with parameters like OrderID, ProductID, UnitPrice, Quantity, and Discount.  
   - Makes UnitPrice and Discount optional.  
   - Uses default values if not provided.  
   - Updates inventory accordingly.  
   - Aborts if insufficient stock.  
   - Notifies when stock drops below reorder level.

2. **UpdateOrderDetails**:  
   - Updates values in Order Details.  
   - All parameters except OrderID and ProductID are optional.  
   - Retains original values using `ISNULL()` if any field is `NULL`.  
   - Adjusts UnitsInStock accordingly.

3. **GetOrderDetails**:  
   - Takes OrderID as input and fetches details.  
   - If no record found, prints:  
     `The OrderID XXXX does not exist.`  
   - Returns value `1` if not found.

4. **DeleteOrderDetails**:  
   - Takes OrderID and ProductID as input.  
   - Deletes order after validating parameters.  
   - Returns `-1` and prints error if invalid.

---

#### 🧮 Functions

1. Create a function that takes a `datetime` input and returns the date in `MM/DD/YYYY` format.  
2. Create a function that takes a `datetime` input and returns the date in `YYYYMMDD` format.  
*(Use: [SQL Server Date Formats](http://www.sql-server-helper.com/tips/date-formats.aspx))*

---

#### 👁️ Views

1. `vwCustomerOrders`:
   - Displays CompanyName, OrderID, OrderDate, ProductID, ProductName, Quantity, UnitPrice, Quantity × UnitPrice.

2. Modified `vwCustomerOrders`:  
   - Same as above, but filtered for orders placed **yesterday**.

3. `MyProducts`:  
   - Shows ProductID, ProductName, QuantityPerUnit, UnitPrice from `Products`  
   - Joins `Suppliers` for CompanyName and `Categories` for CategoryName  
   - Only includes non-discontinued products.

---

#### 🧨 Triggers

1. **Instead of DELETE Trigger on Orders Table**:  
   - When an order is canceled, deletes associated OrderDetails before deleting the order.

2. **BEFORE INSERT Trigger on OrderDetails**:  
   - Checks if sufficient stock is available.  
   - Rejects insertion and alerts user if stock is insufficient.  
   - If sufficient, reduces stock.
