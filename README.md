# Bakery Database Project

This project presents a complete design and implementation of a relational database system for a small bakery. It includes conceptual, logical, and physical models along with SQL scripts for Microsoft SQL Server and Oracle.

## 📑 Table of Contents

- [Project Background]
- [Requirements]
- [Conceptual Model (Chen)]
- [Logical Entities and Attributes]
- [Relationships]
- [Logical and Physical Models]
- [SQL Scripts]
- [Database Schema]
- [Conclusions]

## 📘 Project Background

This database is designed to support bakery operations, such as managing products, orders, suppliers, and employees.

## 📋 Requirements

### Functional:
- Track customer orders and payments
- Manage inventory and suppliers
- Monitor employee roles and schedules

### Non-functional:
- Ensure data consistency and backup
- Allow scalability for new features

## 📐 Conceptual Model (Chen)
[Diagram or PDF reference here]

## 🧱 Logical Entities and Attributes
- Entities: Customers, Orders, Products, Employees, Suppliers, etc.
- Full list available in `docs/entities.pdf` (or in folder)

## 🔗 Relationships
- One-to-many: Customer → Orders
- Many-to-many: Products ↔ Orders (via OrderDetails)

## 🗃️ SQL Scripts
- `create_tables.sql`
- `insert_sample_data.sql`
- `create_views.sql`
- `create_indexes.sql`

## 🧾 Technologies Used
- Microsoft SQL Server
- Oracle SQL
- Microsoft Access (optional early-stage modeling)

## ✅ Conclusions

The project illustrates the complete process of designing a relational database system from concept to implementation.

---

## 📂 How to Run

You can run the SQL scripts in:
- Microsoft SQL Server Management Studio (SSMS)
- Oracle SQL Developer (with minor adjustments)

---
