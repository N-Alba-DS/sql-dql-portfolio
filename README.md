#  SQL Practice Portfolio — Relational Models

This notebook compiles the resolution of 50 practical exercises from the course **Relational Models**, part of the Data Science Master's program at the University of Buenos Aires.  
It demonstrates SQL proficiency applied to real business contexts using the `AdventureWorks` database. The exercises were originally resolved on a on a SQL Server using Dbeaver as a main Database Tool and then were ported into Python by using SQLite3.

The exercises cover essential aspects of working with relational databases, including basic queries, joins, aggregation, subqueries, common table expressions (CTEs), and logical modeling of entity relationships.

---

##  Thematic Index by Conceptual Unit

### 🔍 1. Fundamentals of SQL Querying
*Using SELECT, WHERE, LIKE, logical operators, and NULL handling.*

- Exercises 1–5: Basic filtering and text patterns  
- Exercises 6–11: Column selection, aliases, predicates, data types

---

### 🔗 2. Joins and Table Relationships  
*Relational design in practice. Primary and foreign key logic. Table associations.*

- Exercises 12–16: Basic joins, LEFT JOIN, INNER JOIN, relationship interpretation  
- Exercises 32–39: Multi-table integration — employees, customers, products, addresses

---

### 📊 3. Aggregation, Grouping, and Scalar Functions  
*Applying COUNT, SUM, AVG, MIN, MAX with and without GROUP BY. Use of HAVING.*

- Exercises 17–31: Metrics by group, conditional grouping, sales & stock analysis  
- Exercises 25, 28–30: Multi-variable aggregation and time-based segmentation

---

### 📦 4. Subqueries and Common Table Expressions (CTEs)  
*Modular SQL logic with CTEs. Replacing correlated subqueries. Query chaining.*

- Exercise 48: Rewriting correlated subqueries as CTEs  
- Exercise 49: Last order per customer via subselect  
- Exercise 50: Employee and department-level average rate analysis

---

### 🧮 5. Logical Modeling and Cross-Analysis  
*Cartesian products, territory-based analysis, geographic and customer segmentation.*

- Exercises 40–41: Full cartesian product of entities  
- Exercises 45–46: Regional sales and address metrics

---

### 📈 6. Business-Oriented Query Applications  
*Customer behavior analysis, employee efficiency, detecting unsold or incomplete records.*

- Exercises 35–37: Identifying unsold or undescribed products  
- Exercise 43: Employee segmentation by location  
- Exercise 47: Inventory aggregation by location

---

## ⚙️ Tools & Environment

- 🔹 Language: SQL (SQLite3 dialect)  
- 🔹 Environment: Jupyter Notebook with Python  
- 🔹 Database: AdventureWorks adapted to SQLite  
- 🔹 Output visualization: `pandas.read_sql_query()`

---

## 📌 Why It Matters

This notebook demonstrates foundational SQL skills applied to business data analysis — a key ability for roles such as **Data Analyst**, **Data Scientist**, or **BI Developer**.  
It also highlights competencies in:

- Relational logic and complex query construction  
- Business data model interpretation  
- Query optimization using CTEs  
- Customer segmentation and behavioral analysis
