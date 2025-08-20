# AS_Alias

This repository demonstrates the use of **SQL Aliases (`AS`)** in SQLite to make query results easier to read.

## 📄 Project Description
The query in this project renames columns to more descriptive titles when displaying customer information. This helps improve clarity in reports and makes data easier for non-technical users to understand.

## 🗂 Files in this Repository
- `AS_Alias.db` → SQLite database file used for practice
- `alias_query.txt` → SQL query file showing how aliases are applied
- `alias_results.png` (or your screenshot name) → Screenshot of query output
- `README.md` → Documentation for the project

## 🧑‍💻 Example Query
```sql
SELECT
  FirstName AS 'Customer First Name',
  LastName  AS 'Customer Last Name',
  Email     AS 'Email'
FROM
  Customer;
