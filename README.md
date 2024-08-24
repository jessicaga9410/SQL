# SQL
Jessica's SQL Portfolio
Welcome to my SQL portfolio! This repository showcases a series of projects demonstrating my expertise in SQL using SQLite, Tableau, and Excel. Each project highlights different aspects of data analysis, manipulation, and visualization.

SQLite: Lightweight database engine for running SQL queries and managing data.
Tableau: Data visualization tool for creating interactive dashboards and visualizations.
Excel: Spreadsheet software for data cleaning, preliminary analysis, and visualization.


playful representation of a simple database schema
     +---------------------+
     |      Customers      |
     +---------------------+
     | CustomerID (PK)     |
     | Name                |
     | Email               |
     +---------------------+
               |
               |
               v
     +---------------------+
     |       Orders        |
     +---------------------+
     | OrderID (PK)        |
     | CustomerID (FK)     |
     | OrderDate           |
     | TotalAmount         |
     +---------------------+
               |
               |
               v
     +---------------------+
     |      Products       |
     +---------------------+
     | ProductID (PK)      |
     | Name                |
     | Price               |
     +---------------------+
               |
               |
               v
     +---------------------+
     | OrderDetails        |
     +---------------------+
     | OrderDetailID (PK)  |
     | OrderID (FK)        |
     | ProductID (FK)      |
     | Quantity            |
     | UnitPrice           |
     +---------------------+
