# Task-4
# SQL PROJECT
# 🎯 Objective

    Use SQL queries to extract, manipulate, and analyze structured data from the Netflix Titles dataset. 
    Apply SQL techniques like filtering, aggregation, subqueries, and views to derive insights.
# 📂 Files Included
| **File Name**           | **Description**                                             |
| ----------------------- | ----------------------------------------------------------- |
| `netflix_titles.csv`    | Raw dataset containing Netflix show/movie metadata          |
| `netflix_db_schema.sql` | SQL code to create the `netflix_titles` table               |
| `netflix_analysis.sql`  | SQL file with queries for analysis (SELECT, GROUP BY, etc.) |
| `query_outputs/` folder | Contains screenshots or result exports from SQL queries     |
# 🛠️ Tools Used
| **Tool**         | **Purpose**                                      |
| ---------------- | ------------------------------------------------ |
| MySQL Workbench  | Run SQL queries, import CSV, and view results    |
| MySQL Database   | Store structured data and perform SQL operations |
| CSV File         | Source data file for analysis                    |
| (Optional) Excel | Preview and pre-clean CSV before importing       |
# ✨ Features Demonstrated
| **Feature**                | **Description / Example**                                                      |
| -------------------------- | ------------------------------------------------------------------------------ |
| Basic SQL Commands         | `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`                                      |
| Aggregate Functions        | `COUNT()`, `MAX()`, `MIN()`, `AVG()` used for summaries                        |
| Subqueries                 | Example: `SELECT * FROM netflix_titles WHERE release_year = (SELECT MAX(...))` |
| Views                      | Created with `CREATE VIEW top_genres AS ...`                                   |
| Index Optimization         | Example: `CREATE INDEX idx_country ON netflix_titles(country);`                |
| Data Importing             | `LOAD DATA LOCAL INFILE` used to load CSV into MySQL                           |
| Date Formatting (Optional) | Converted `date_added` using `STR_TO_DATE(date_added, '%M %d, %Y')`            |
# ✨ Features Implemented
# 🧪 Sample Queries for Analysis:
# 1. Total shows by type
![Screenshot 2025-06-08 155756](https://github.com/user-attachments/assets/24c59672-3158-403c-b499-8b90adee20a3)
# 2. Top 5 countries by number of shows
![Screenshot 2025-06-08 155835](https://github.com/user-attachments/assets/9ba6bfd9-3ddb-46e5-a16b-b385977cf3fa)
# 3. Most frequent ratings
![Screenshot 2025-06-08 155906](https://github.com/user-attachments/assets/455245eb-66d6-4a21-80c6-b56c5edd81cd)
# 4. Recent year releases
![Screenshot 2025-06-08 155951](https://github.com/user-attachments/assets/9f177d05-9883-4fa4-8f3f-33fa3fb807fa)
# 5. Top 5 directors with most shows
![Screenshot 2025-06-08 160036](https://github.com/user-attachments/assets/2893975e-6d69-44d9-bbfd-a3d5016a7254)
6. Subquery – Shows released in the latest year
![Screenshot 2025-06-08 160118](https://github.com/user-attachments/assets/bacc8673-212b-4e84-8760-d918b0646ac2)
7. Create View – Top Genres (from listed_in)
![Screenshot 2025-06-08 160229](https://github.com/user-attachments/assets/0c6051bd-384d-4ede-bb30-98efc5a1cb0c)







