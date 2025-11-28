# Olist E-Commerce Analysis with SQL & Python

## Project Overview
This project analyzes the **Brazilian E-Commerce Public Dataset by Olist**, covering 100k orders made between 2016 and 2018. The goal is to derive actionable business insights regarding logistics performance, customer payment behavior, and sales trends using **SQL** for data manipulation and **Python** for visualization.

## Key Insights
1.  **Logistics Challenges:** Customers in Northern states (e.g., Roraima, Amapá) experience delivery times 3x longer (avg. 28 days) than customers in the South (avg. 8-10 days).
2.  **Credit Card Installments:** There is a strong positive correlation between the number of installments and the average order value. Customers splitting payments into 10 installments spend ~400% more than those paying upfront.
3.  **Peak Shopping Times:** The highest volume of orders occurs between 10:00 AM and 4:00 PM on weekdays.

## Tech Stack
* **SQL (SQLite):** Complex queries, JOINs, aggregations, window functions.
* **Python:** Pandas (Data processing), Matplotlib/Seaborn (Visualization).
* **Jupyter Notebook:** Interactive reporting.

## Dataset
The dataset is provided by Olist on Kaggle: [Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).
*Note: Data files are not included in this repo due to size limits.*

## How to Run
1.  Download the dataset from Kaggle.
2.  Place CSV files in the root directory.
3.  Run `Olist_Analysis_SQL.ipynb` in Jupyter Notebook.
