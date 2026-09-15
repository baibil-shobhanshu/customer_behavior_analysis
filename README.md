# 📊 Data Analytics Project

## Overview

This project demonstrates an end-to-end **Data Analytics workflow**, starting from raw data loading and exploration in Python to SQL-based analysis in MySQL and interactive dashboard creation in Power BI.

The objective of the project is to clean and analyze the dataset, identify meaningful business insights, and present the findings through an interactive dashboard.

---

## Dataset

The dataset contains structured business-related data used to perform exploratory analysis and generate insights.

**Dataset includes:**

* Customer / transaction information
* Product or category details
* Sales and revenue information
* Date and location-related fields
* Other relevant business attributes

The dataset was initially loaded into Python for data inspection, cleaning, and exploratory data analysis.

---

## Tools & Technologies

* **Python** – Data loading, cleaning, and Exploratory Data Analysis (EDA)
* **Pandas** – Data manipulation and preprocessing
* **Matplotlib / Seaborn** – Data visualization
* **MySQL** – SQL-based data analysis and querying
* **Power BI** – Interactive dashboard and data visualization
* **Jupyter Notebook** – Python-based analysis

---

## Steps

### 1. Load Data

The dataset was imported into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")
```

Initial checks were performed to understand:

* Number of rows and columns
* Data types
* Missing values
* Duplicate records
* Basic statistics

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand the structure and characteristics of the data.

Key activities included:

* Checking distributions
* Identifying trends and patterns
* Analyzing categorical and numerical columns
* Finding outliers
* Examining relationships between variables
* Creating charts for important business metrics

### 3. Data Cleaning

The dataset was cleaned and prepared for further analysis.

Main activities included:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Formatting date columns
* Handling inconsistent values
* Removing or treating irrelevant records
* Creating required calculated fields

### 4. SQL Analysis – MySQL

The cleaned dataset was loaded into a **MySQL server** for further analysis.

SQL queries were used to answer business questions and extract meaningful insights.

Key SQL concepts used:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `HAVING`
* `ORDER BY`
* Aggregate functions
* `CASE WHEN`
* `JOIN`
* Subqueries
* CTEs
* Window Functions

Examples of analysis included:

* Total sales and revenue
* Top-performing products/categories
* Sales by time period
* Customer or regional performance
* Average and total metrics
* Ranking and comparison analysis

### 5. Power BI Dashboard

The analyzed data was connected to **Power BI** to create an interactive dashboard.

The dashboard includes:

* KPI cards
* Sales/revenue analysis
* Trend analysis
* Category/product performance
* Interactive filters and slicers
* Charts and visualizations
* Business performance indicators

---

## Dashboard

The Power BI dashboard provides an interactive view of the key business metrics and insights discovered during the analysis.

**Key dashboard metrics:**

* Total Revenue
* Total Sales
* Total Orders
* Average Sales
* Top Products / Categories
* Monthly or Yearly Trends
* Regional / Customer Performance

> 📌 Power BI dashboard.

<img width="3981" height="2575" alt="customer_shopping_behaviour_power_bi_page-0001" src="https://github.com/user-attachments/assets/124bbce5-a381-42e6-b452-55504681bc10" />


---

## Results

The analysis helped identify important business trends and performance indicators from the dataset.

### Key Insights

* Identified the highest-performing products/categories.
* Analyzed sales and revenue trends over time.
* Identified areas with strong and weak performance.
* Compared performance across different categories or regions.
* Used SQL analysis to answer important business questions.
* Created an interactive Power BI dashboard for easier decision-making.

The project demonstrates the complete workflow of transforming **raw data into actionable business insights**.

## Conclusion

This project demonstrates an end-to-end **Data Analyst workflow**, covering data preparation, exploratory analysis, SQL querying, and business intelligence dashboard development.

It showcases the ability to transform raw data into meaningful insights and communicate those insights through clear and interactive visualizations.
