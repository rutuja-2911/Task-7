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
- **Python** (with built-in `sqlite3`)
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

### Sample Data:
```plaintext
('Apple', 10, 1.50)
('Banana', 20, 0.80)
('Orange', 15, 1.20)
('Apple', 5, 1.50)
('Banana', 10, 0.80)
('Orange', 10, 1.20)
