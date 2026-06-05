# Customer Shopping Behavior Analysis

## Overview

This project focuses on analyzing customer shopping behavior using Python, MySQL, and Power BI. The workflow includes data loading, exploratory data analysis (EDA), data cleaning, SQL-based business analysis, and dashboard development to uncover customer purchasing patterns and generate actionable insights.

The project demonstrates an end-to-end data analytics pipeline, from raw data preparation to interactive business intelligence reporting.

---

## Dataset

The dataset contains customer shopping information, including:

* Customer demographics
* Product categories
* Purchase amounts
* Review ratings
* Payment methods
* Subscription status
* Shopping frequency
* Discounts and promotions

The data was used to analyze customer behavior, spending patterns, and overall business performance.

---

## Tools & Technologies

### Programming & Analysis

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

### Database

* MySQL

### Business Intelligence

* Power BI

### Development Environment

* Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

* Imported the dataset using Pandas.
* Examined dataset structure, data types, and missing values.

### 2. Exploratory Data Analysis (EDA)

* Generated summary statistics.
* Analyzed distributions of key variables.
* Identified trends and patterns in customer purchases.
* Created visualizations to understand customer behavior.

### 3. Data Cleaning

* Handled missing values.
* Removed duplicate records.
* Standardized column formats.
* Corrected data inconsistencies.

### 4. SQL Analysis (MySQL)

Performed SQL queries to answer business questions such as:

* Total revenue generated.
* Average customer spending.
* Subscription vs non-subscription customer analysis.
* Product category performance.
* Customer rating analysis.
* Purchase frequency trends.

### 5. Dashboard Development

Built an interactive Power BI dashboard to visualize:

* Revenue metrics
* Customer demographics
* Product performance
* Subscription insights
* Purchase trends
* Customer satisfaction indicators

---

## Dashboard Features

The Power BI dashboard includes:

* KPI Cards for key business metrics
* Revenue and spending analysis
* Customer segmentation insights
* Product category performance tracking
* Review rating analysis
* Interactive filters and slicers
* Dynamic visualizations for decision-making

  <img width="1186" height="661" alt="image" src="https://github.com/user-attachments/assets/e3d146fb-b487-4439-a366-08103fde3de1" />

---

## Key Results

Some key insights obtained from the analysis include:

* Identification of top-performing product categories.
* Understanding customer spending behavior.
* Comparison of subscribed and non-subscribed customers.
* Analysis of customer satisfaction through review ratings.
* Discovery of trends influencing purchase frequency and revenue generation.

---

## Project Structure

```text
├── customer_shopping_Project.ipynb      # Python analysis and EDA
├── customer_behavior_sqlqueries.sql     # SQL queries for business analysis
├── customer_behavior_dashboard.pbix     # Power BI dashboard
├── dataset.csv                          # Source dataset
└── README.md
```

---

## How to Run

### Step 1: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn mysql-connector-python
```

### Step 2: Run Python Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook customer_shopping_Project.ipynb
```

Run all cells to perform:

* Data loading
* Data cleaning
* EDA
* Visualization

### Step 3: Execute SQL Queries

1. Import the dataset into MySQL.
2. Open `customer_behavior_sqlqueries.sql`.
3. Execute the queries using MySQL Workbench.

### Step 4: View Dashboard

Open:

```text
customer_behavior_dashboard.pbix
```

using Power BI Desktop to explore the interactive dashboard.

---

## Conclusion

This project demonstrates a complete data analytics workflow by combining Python for data preparation and analysis, MySQL for business querying, and Power BI for interactive visualization. The insights generated can support data-driven decision-making and improve understanding of customer purchasing behavior.
