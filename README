# Northwind SQL Sales Analysis

**Author:** Devangi Kanyal  
**Date:** June 11, 2025

This project showcases a comprehensive SQL-based analysis of the Northwind Traders dataset, a classic sample database that simulates a small international trading company. The analysis includes sales trends, customer behavior, product demand, and employee performance — providing a strong demonstration of SQL querying and business intelligence skills.

---

## 📊 Project Overview

The analysis answers several key business questions using SQL queries, such as:

1. **Top 10 Customers by Revenue**  
2. **Most Frequently Ordered Products**  
3. **Monthly Sales Trends**  
4. **Sales by State/Province**  
5. **Average Order Value per Order**  
6. **Customer Retention and Loyalty Insights**  
7. **Common Product Pairings (Basket Analysis)**  
8. **Employee Sales Performance**  
9. **Order Fulfillment Time**  
10. **Inventory Alerts for Low Stock Products**

---

## 🗃️ Dataset

The [Northwind database](https://github.com/jpwhite3/northwind-MySQL) includes:
- `Customers`, `Orders`, `Order_Details`
- `Products`, `Employees`, `Suppliers`
- Geographical info such as `Country_region` and `State_province`

---

## 🛠️ Tools Used

- **MySQL Workbench**
- **SQL (MySQL dialect)**
- **Northwind Sample Database**

---

## 📌 Sample Query

```sql
-- Most Frequently Ordered Products
SELECT p.id, p.Product_Name, 
       SUM(od.Quantity) AS TotalUnitsSold
FROM Order_Details od
JOIN Products p USING (id)
GROUP BY p.id, p.Product_Name
ORDER BY TotalUnitsSold DESC
LIMIT 10;
