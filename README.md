# Customer_Shopping_Behavior_Analysis
End-to-end customer behavior analysis using SQL for data extraction, Python for EDA &amp; statistical modeling, and Power BI for interactive dashboard visualization.

## Overview

This project presents an end-to-end data analytics solution to analyze customer shopping behavior using transactional data. The objective is to identify spending patterns, customer segments, product preferences, and subscription trends to generate actionable business insights.

The project workflow covers the complete analytics pipeline:

- Data loading and exploration using Python
- Exploratory Data Analysis (EDA)
- Data cleaning and feature engineering
- SQL-based business analysis using PostgreSQL
- Interactive dashboard development using Power BI
- Business reporting and presentation creation using Gamma

The analysis helps understand customer purchasing patterns and supports data-driven decision-making.

---

## Dataset

**Dataset Name:** Customer Shopping Behavior Dataset

**Dataset Size:**
- Rows: 3,900
- Columns: 18

The dataset contains customer transaction records covering:

### Customer Information
- Age
- Gender
- Location
- Subscription Status

### Purchase Details
- Item Purchased
- Category
- Purchase Amount
- Season
- Size
- Color

### Shopping Behavior
- Discount Applied
- Promo Code Used
- Previous Purchases
- Frequency of Purchases
- Review Rating
- Shipping Type

The dataset contained **37 missing values in the Review Rating column**, which were handled during the data cleaning process. 

---

## Tools & Technologies

### Programming and Data Analysis
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Database
- PostgreSQL Server
- SQL Queries

### Visualization
- Power BI

### Reporting and Presentation
- Gamma
- Microsoft PowerPoint

---

## Project Workflow

## 1. Data Loading and Exploration (Python)

The dataset was imported into Python using Pandas.

Initial analysis included:

- Checking dataset structure using `df.info()`
- Generating summary statistics using `describe()`
- Understanding data distributions and patterns

EDA was performed to identify trends, relationships, and potential data quality issues. 

---

## 2. Data Cleaning and Preparation

The following preprocessing steps were performed:

- Checked and handled missing values
- Imputed missing review ratings using the median rating of each product category
- Standardized column names using snake_case format
- Created new features:
  - Age group classification
  - Purchase frequency in days
- Removed redundant columns after consistency checks

The cleaned dataset was then connected from Python to PostgreSQL for further analysis.

---

## 3. SQL Analysis Using PostgreSQL

The cleaned data was loaded into PostgreSQL and analyzed using SQL queries to answer important business questions.

Key analyses included:

- Revenue comparison by gender
- Identifying high-spending discount users
- Finding top-rated products
- Comparing Standard vs Express shipping performance
- Comparing subscribers and non-subscribers
- Identifying discount-dependent products
- Customer segmentation
- Finding top products by category
- Analyzing repeat buyers and subscription behavior
- Revenue contribution by age group

These SQL analyses provided insights into customer behavior and purchasing trends. 

---

## 4. Power BI Dashboard

An interactive Power BI dashboard was developed to visualize key findings from the analysis.

Dashboard features include:

- Customer purchasing trends
- Revenue analysis
- Product performance
- Customer segmentation
- Subscription insights
- Interactive filters for exploration

The dashboard enables users to quickly understand customer behavior and business performance.

---

## Results and Business Insights

The analysis generated several actionable insights:

- Subscription programs can be improved by promoting exclusive benefits.
- Loyalty programs can encourage repeat customers to become loyal buyers.
- Discount strategies should be balanced to increase sales while maintaining profit margins.
- Best-selling and highly rated products can be highlighted in marketing campaigns.
- Targeted marketing can focus on high-revenue customer groups.




