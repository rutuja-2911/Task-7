# Task-7: Get Basic Sales Summary from a Tiny SQLite Database using Python

## Task Overview
**Objective:**  
Create a simple Python script or Jupyter Notebook that connects to a small SQLite database, runs basic SQL queries to summarize sales data, and visualizes the results using a bar chart.

This task demonstrates how to:
- Interact with SQLite databases using Python
- Perform SQL-based aggregation
- Display results with print statements
- Visualize data using matplotlib

## Tools Used
- **Python** 
- **pandas** for data manipulation
- **matplotlib** for data visualization
- **Jupyter Notebook**

## Dataset
The script creates a small SQLite database file named `sales_data.db`, containing one table:

### `sales` Table Schema:
| Column   | Type    | Description              |
|----------|---------|--------------------------|
| id       | INTEGER | Primary Key (auto-incremented) |
| product  | TEXT    | Name of the product       |
| quantity | INTEGER | Quantity sold             |
| price    | REAL    | Price per unit            |


##  What It Does
1. **Creates** a SQLite database `sales_data.db` (if it doesn't already exist)
2. **Creates and populates** a `sales` table with sample data
3. **Performs** SQL aggregation:
   - Total quantity sold per product
   - Total revenue (quantity × price) per product
4. **Prints** the summary using pandas
5. **Visualizes** the revenue by product using a simple bar chart
6. **Saves** the chart as `sales_chart.png`

## Output Chart
![Alt text](C:\Users\kunal#2000\Downloads\Task 7)
