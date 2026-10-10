# DecodeLabs-Internship-Project03
# SQL Data Analysis: Project 3

**DecodeLabs Data Analytics Internship**

## Overview
This project uses SQL queries to analyze a dataset and answer business questions. It covers filtering, sorting, grouping, and summarizing data to find useful insights.

## Files in this repository

| File | Description |
|------|-------------|
| `SQL_Data_Analysis_Project3.xlsx` | The dataset with the solved queries and results |
| `SQL_Report_Project3.pdf` | A report explaining the queries, results, and findings |

## SQL concepts used
- `SELECT`: choosing the columns to display
- `WHERE`: filtering rows by a condition
- `ORDER BY`: sorting results in ascending or descending order
- `GROUP BY`: grouping rows by a category
- `COUNT`, `SUM`, `AVG`: summarizing the data
- `HAVING`: filtering the groups after aggregation

## Example queries

```sql
-- Total sales per category, highest first
SELECT Category, SUM(Sales) AS Total_Sales
FROM Orders
GROUP BY Category
ORDER BY Total_Sales DESC;

-- Categories with more than 50 orders
SELECT Category, COUNT(*) AS Order_Count
FROM Orders
GROUP BY Category
HAVING COUNT(*) > 50;
```
*(Replace these with your own queries and column names.)*

## Key findings
- [Finding 1, e.g. which category has the highest sales]
- [Finding 2, e.g. average order value]
- [Finding 3]

## Tools used
- SQL
- Microsoft Excel

## Author
**Bilal**
BSIT Student, Lahore Garrison University
Aspiring Data Analyst
