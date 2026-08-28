# Basic Sales Summary from a Tiny SQLite Database using Python

## Objective
Use SQL inside Python to pull simple sales info (total quantity sold, total revenue) from a small SQLite database, and display it using print statements and a bar chart.

## Tools Used
- Python
- sqlite3 (built-in)
- pandas
- matplotlib
- Jupyter Notebook

## What I Did
1. Created a SQLite database (sales_data.db) with a single sales table containing columns: product, quantity, price, sale_date.
2. Inserted 12 sample sales records across 4 products (Notebook, Pen, Backpack, Water Bottle).
3. Connected to the database using Python's sqlite3 module.
4. Ran a SQL query with GROUP BY to calculate total quantity sold and total revenue per product.
5. Loaded the SQL results into a pandas DataFrame using pd.read_sql_query().
6. Printed the summary table to the console.
7. Created a bar chart of revenue by product using matplotlib.
8. Saved the chart as sales_chart.png.

## Output
| Product | Total Qty | Revenue |
|---|---|---|
| Backpack | 9 | $162.0 |
| Water Bottle | 24 | $144.0 |
| Notebook | 27 | $67.5 |
| Pen | 70 | $52.5 |

