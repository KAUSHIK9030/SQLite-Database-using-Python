# TASK-7-DA: Basic Sales Summary with SQLite and Python

## Overview

This project creates a basic sales summary by connecting to an SQLite database, querying sales data, and visualizing the results using a bar chart. The task involves using Python with libraries such as `sqlite3`, `pandas`, and `matplotlib`.

## Objectives

-   Connect to an SQLite database (`sales_data.db`).
-   Execute SQL queries to retrieve and summarize sales data.
-   Display the output using print statements.
-   Create a bar chart to visualize the summarized data.

## Tools Used

-   Python
-   `sqlite3`
-   `pandas`
-   `matplotlib`
-   Google Colab
-   SQLite

## Files Included

-   `sales_data_sample.csv`: The dataset used for creating the SQLite database.
-   `sales_data.db`: The SQLite database file (containing sales data).
-   `SQLite_Sales_Database.ipynb`: The Google Colab notebook containing the Python code.
-   `Screenshot [Date].png`: A screenshot of the generated bar chart.
-   `README.md`: This file, providing an overview of the project.

## Setup

1.  **Create SQLite Database:**

    *   Load the `sales_data_sample.csv` file into a `pandas` DataFrame.
    *   Create an SQLite database named `sales_data.db`.
    *   Create a table named `sales`.
    *   Insert the data from the DataFrame into the `sales` table.

2.  **Python Script (Google Colab Notebook):**

    *   Connect to the SQLite database.
    *   Execute SQL queries to calculate total quantity sold and total revenue per product.
    *   Fetch the results into a `pandas` DataFrame.
    *   Create a bar chart using `matplotlib` to visualize the top products by revenue.
    *   Save the chart as "Screenshot".

## Usage

1.  Open the `SQLite_Sales_Database.ipynb` file in Google Colab.
2.  Ensure that the `sales_data_sample.csv` file is accessible to the notebook (e.g., uploaded to Colab).
3.  Run the notebook to:
    *   Create the `sales_data.db` database file.
    *   Execute the SQL query and display the results.
    *   Generate
