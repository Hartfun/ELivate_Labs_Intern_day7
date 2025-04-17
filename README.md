Analyze and visualize sales data using Matplotlib
Technologies Used:
Python
SQLite3
Pandas
Matplotlib

Key Features:
Database Connection
Uses sqlite3 to connect to a local sales_data.db database.

SQL Query Execution":
Runs SQL queries to aggregate sales data such as:
Total quantity sold, Total revenue by product
Total quantity sold per Category

DataFrame Operations:
Loads SQL results into Pandas DataFrames for easy manipulation and visualization.

Data Visualization:
Bar charts to show:
Sales by Payment Method
Units Sold vs Unit Price

Pie chart to show:
Sales distribution by Product Category

Saves charts to image files using plt.savefig()
