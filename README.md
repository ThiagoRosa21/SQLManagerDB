<div align="center"><h1> EmployeeDB 🚀 </h1></div>

<div align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/T-SQL-CC2927?logo=microsoftsqlserver&logoColor=fff" alt="T-SQL Badge" width="100">
  </a>
</div>

**A structured database project using T-SQL for managing employee data efficiently. This repository includes database scripts, stored procedures, views, triggers, and indexes to optimize performance and data integrity.**

---

## Features
- 🛠 **Database Creation**: Scripts to create and configure the EmployeeDB.
- 📄 **Schema Definition**: Tables and relationships properly structured.
- ⚡ **Stored Procedures & Triggers**: Automating database operations.
- 📊 **Optimized Indexes & Views**: Ensuring query performance and easy data retrieval.

---

## Technologies Used 💻
- **T-SQL**: Used for database management.
- **Microsoft SQL Server**: The database engine used in this project.

---

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/ThiagoRosa21/EmployeeDB
cd EmployeeDB
```

### Run the Scripts in Order:
1. Create the database
```bash
sqlcmd -S SERVER_NAME -i scripts/01_create_database.sql
```
2. Create tables
```bash
sqlcmd -S SERVER_NAME -i scripts/02_create_tables.sql
```
3. Insert sample data
```bash
sqlcmd -S SERVER_NAME -i scripts/03_insert_data.sql
```
4. Run additional configurations (procedures, triggers, indexes)
```bash
sqlcmd -S SERVER_NAME -i scripts/04_stored_procedures.sql
sqlcmd -S SERVER_NAME -i scripts/05_triggers.sql
sqlcmd -S SERVER_NAME -i scripts/06_views.sql
sqlcmd -S SERVER_NAME -i scripts/07_functions.sql
sqlcmd -S SERVER_NAME -i scripts/08_indexes.sql
```

---

## File Structure
```bash
EmployeeDB/
├── scripts/
│   ├── 01_create_database.sql
│   ├── 02_create_tables.sql
│   ├── 03_insert_data.sql
│   ├── 04_stored_procedures.sql
│   ├── 05_triggers.sql
│   ├── 06_views.sql
│   ├── 07_functions.sql
│   ├── 08_indexes.sql
├── docs/
│   ├── schema.png
│   ├── queries_examples.sql
├── exemplos/
│   ├── consultas.sql
├── tests/
│   ├── test_cases.sql
├── .gitignore
├── LICENSE
└── README.md
```

# Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.
