# 🍔 End-to-End Business Analytics on Swiggy Orders using Advanced SQL.

**Project Overview:** Designed and implemented an end-to-end SQL analytics solution on simulated Swiggy transactional data (100K+ records) to analyze customer behavior, restaurant performance, delivery efficiency, and revenue trends using complex joins, window functions, CTEs, and advanced aggregations.

---

## 🔹 Business Problem
Online food delivery platforms like Swiggy generate massive transactional data every day. Business teams require actionable insights on:
* Customer ordering behavior
* Restaurant performance
* Delivery efficiency
* Revenue trends
* Peak demand patterns

This project aims to convert raw transactional data into meaningful business intelligence using SQL.

## 🔹 Objective
To build a complete SQL-based analytics solution that answers real business questions related to:
* Sales performance
* Customer behavior
* Restaurant efficiency
* Delivery time optimization

---

## 🔹 Dataset Description
The dataset simulates real Swiggy platform data containing **~100K+ simulated rows** across the following tables:

| Table | Description |
| :--- | :--- |
| `users` | Customer profiles |
| `restaurants` | Restaurant master data |
| `orders` | Transaction level orders |
| `order_items` | Item-level details |
| `delivery` | Delivery time and distance |
| `ratings` | Customer ratings|

---

## 🔹 Key Business Questions Solved

### 🔸 Customer Analytics
* Who are the most valuable customers?
* What is the repeat ordering behavior?
* What is the average order value per user?

### 🔸 Sales & Revenue Analysis
* Daily / weekly / monthly revenue trends
* Peak ordering hours
* Weekend vs weekday demand

### 🔸 Restaurant Performance
* Top performing restaurants by Revenue, Order volume, and Ratings
* Underperforming restaurants

### 🔸 Delivery Optimization
* Average delivery time
* Impact of distance on delivery
* Peak-time delivery delays

---

## 🔹 Key Insights Generated
* **Power user concentration:** 20% of customers generate ~65% of total revenue.
* **Staffing & logistics optimization:** Peak demand occurs between 7 PM – 10 PM.
* **Demand trends:** Weekend orders are 38% higher than weekdays.
* **Logistics bottlenecks:** Delivery delays spike during rain and peak hours.

## 🔹 Business Impact
* Helps optimize delivery workforce allocation
* Improves restaurant onboarding & ranking strategy
* Supports dynamic pricing & promotions
* Enables customer loyalty targeting

---

## 🔹 SQL Techniques & Skills Demonstrated

| Category | SQL Features Used |
| :--- | :--- |
| **Aggregation** | `SUM()`, `AVG()`, `COUNT()`, `MIN()`, `MAX()`|
| **Filtering & Sorting** | `WHERE`, `HAVING`, `ORDER BY`|
| **Grouping** | `GROUP BY` |
| **Joins** | `INNER JOIN`, `LEFT JOIN` |
| **Window Functions** | `RANK()`, `DENSE_RANK()`, `ROW_NUMBER()` |
| **Advanced Queries** | Subqueries (Nested queries), CTEs (`WITH` clause) |
| **Date Functions** | `DATE`, `EXTRACT`, `INTERVAL` |

**Core Skills:** Advanced SQL, Business analytics, KPI development, Data-driven decision making, Query optimization.

## 🔹 Tools & Technologies
* SQL (PostgreSQL / MySQL / BigQuery compatible syntax)
* SQL Workbench / DBeaver
* GitHub for version control
