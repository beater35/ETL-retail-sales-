# Retail Sales ETL Project

This is a simple ETL (Extract, Transform, Load) project using a retail sales dataset. The project demonstrates basic data cleaning, transformation, loading into an SQLite database, and querying for analysis with visualization.

---

## Project Overview

The goal of this project is to simulate a real-world ETL pipeline by performing the following steps:

- **Extract:** Upload and load a CSV dataset containing retail sales data.
- **Transform:** Clean the data, handle missing values, convert date columns, and add calculated fields like shipping duration and discounted sales.
- **Load:** Store the cleaned and transformed data into an SQLite database for querying.
- **Analyze:** Run SQL queries to generate insights such as total sales by region and monthly sales trends.
- **Visualize:** Create plots to visualize sales trends over time.

---

## Dataset

The dataset used is a retail sales dataset (~10,000 rows, 25 columns) with information such as order dates, customer details, product categories, sales, discounts, and profits.

---

## Technologies & Tools

- Python 3.x
- Pandas
- SQLite (in-memory)
- Matplotlib
- Google Colab (recommended for running the notebook)

---

## How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/retail-sales-etl.git

2. Open the Jupyter Notebook (retail_sales_etl.ipynb) in Google Colab or your local environment.

3. Upload the dataset CSV when prompted in the notebook.

4. Run the notebook cells sequentially to perform ETL and analysis.

## Notes

- This is a basic ETL example designed for learning and demonstration purposes.
- In production, ETL pipelines are automated with tools like Apache Airflow.
- Data is loaded into an SQLite in-memory database for simplicity; scalable solutions can use cloud databases.

---
