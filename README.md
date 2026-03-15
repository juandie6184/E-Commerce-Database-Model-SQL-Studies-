# 🛒 E-Commerce Database Model (SQL Practices)

This repository contains a relational e-commerce database model I designed from scratch, along with practice files documenting my core SQL skills.

It was created to build a solid database foundation for an "E-Commerce Admin Panel" project I plan to develop with C# in the future, taking my first steps into full-stack development.

## 📂 Project Content and Steps

The `.sql` files in this project demonstrate the step-by-step process from setting up a database architecture to making it ready for analytical reporting:

1. **`eticaret_tablolar.sql`**: Building the database skeleton. Connecting Category, Product, Customer, and Order tables using `PRIMARY KEY` and `FOREIGN KEY` relationships.
2. **`ornek_veriler_ekleme.sql`**: Inserting test data into the created tables using `INSERT INTO` commands.
3. **`join_kullanimi.sql`**: Meaningfully combining data from different tables (e.g., Products and Categories) using `INNER JOIN`.
4. **`musteri_siparis_raporlari.sql`**: Extracting analytical reports, such as total spending per customer, using `GROUP BY` and `SUM` functions.
5. **`view_olusturma.sql`**: Packaging complex reporting queries into virtual tables using `CREATE VIEW` so they can be easily executed from the software application side (e.g., C#).

## 🚀 Key Learnings & Skills

* **DDL (Data Definition Language):** `CREATE TABLE`, `CREATE DATABASE`
* **DML (Data Manipulation Language):** `INSERT INTO`, `SELECT`
* **Relational Database Logic:** Primary and Foreign Keys (PK, FK)
* **Data Analysis & Reporting:** `JOIN`, `GROUP BY`, Aggregate Functions (`SUM`)
* **Database Objects:** `VIEW`

## 🎯 Future Goals

* Integrating this database structure into a backend project using C#.
* Performing dynamic Create, Read, Update, and Delete (CRUD) operations on this database via an admin panel interface.
