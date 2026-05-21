# HEALTHCARE-_SQL_QUERY
# Healthcare Claims Analysis using MySQL & Power BI

## Project Overview

This project analyzes US healthcare insurance claim data using MySQL and Power BI to identify business insights, cost trends, regional risk patterns, and healthcare expense drivers.

The objective of this project is to simulate real-world healthcare analytics by solving business problems using SQL queries, KPI analysis, and dashboard reporting.

---

# Dataset Information

- Source: Kaggle Healthcare Insurance Dataset
- File Format: CSV
- Total Columns: 7

### Dataset Columns

| Column Name | Description |
|-------------|-------------|
| AGE | Age of insured person |
| SEX | Gender of customer |
| BMI | Body Mass Index |
| CHILDREN | Number of dependents |
| SMOKER | Smoking status |
| REGION | Residential region |
| CHARGES | Medical insurance charges |

---

# Project Objectives

This project focuses on:

- Analyzing healthcare insurance costs
- Identifying high-risk customer groups
- Comparing smoker vs non-smoker expenses
- Evaluating regional healthcare trends
- Understanding BMI impact on charges
- Performing KPI and business analysis using SQL

---

# Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| MySQL | Data storage & SQL analysis |
| SQL | Data querying & business analysis |
| Power BI | Dashboard & visualization |
| CSV Dataset | Raw healthcare data |
| GitHub | Project hosting & portfolio |

---

# Project Structure

```text
Healthcare-Claims-Analysis/
│
├── Dataset/
│   └── claims_data.csv
│
├── SQL Queries/
│   ├── schema.sql
│   ├── data_cleaning.sql
│   ├── exploratory_analysis.sql
│   ├── kpi_queries.sql
│   └── advanced_queries.sql
│
├── Dashboard/
│   └── powerbi_dashboard.png
│
├── Insights/
│   └── business_findings.md
│
├── README.md
│
└── screenshots/
    ├── mysql_workbench.png
    └── query_output.png
```

---

# SQL Concepts Used

This project demonstrates:

- SELECT Statements
- WHERE Conditions
- GROUP BY
- ORDER BY
- Aggregate Functions
- CASE WHEN
- Subqueries
- Window Functions
- RANK()
- Common Table Expressions (CTE)
- Data Cleaning Queries

---

# Business Problems Solved

## 1. Regional Healthcare Cost Analysis
Identified which region has the highest average insurance charges.

## 2. Smoker Risk Analysis
Compared healthcare costs between smokers and non-smokers.

## 3. Age Group Cost Segmentation
Analyzed which age group contributes most to insurance expenses.

## 4. BMI Risk Categorization
Evaluated how obesity impacts healthcare costs.

## 5. Gender-Based Charge Analysis
Compared average charges between male and female policyholders.

## 6. Family Dependency Analysis
Studied how the number of children affects medical expenses.

## 7. High-Cost Patient Identification
Found top customers with highest insurance claims.

## 8. Regional Smoking Trend Analysis
Calculated smoker percentage across different regions.

## 9. Region-wise Smoker Cost Comparison
Compared smoker vs non-smoker charges within each region.

## 10. Above Average Cost Patients
Identified customers whose charges exceed overall average charges.

## 11. Regional Charge Ranking
Ranked customers by insurance charges using window functions.

## 12. Combined Obesity & Smoking Risk Analysis
Analyzed healthcare expenses for obese smokers.

---

# Sample SQL Query

```sql
SELECT smoker,
       ROUND(AVG(charges),2) AS avg_charges
FROM insurance
GROUP BY smoker;
```

---

# Key Insights

- Smokers generate significantly higher medical expenses compared to non-smokers.
- Obese customers tend to have higher insurance charges.
- Certain regions show consistently higher healthcare costs.
- Insurance expenses increase with age.
- Combined smoking and obesity create the highest healthcare risk group.

---

# Power BI Dashboard

## Dashboard Preview

> ADD POWER BI DASHBOARD SCREENSHOT HERE

### Dashboard Features

- KPI Cards
- Region-wise Cost Analysis
- Smoker vs Non-Smoker Comparison
- BMI Distribution
- Age Group Analysis
- Interactive Filters

---

# Screenshots

## MySQL Workbench

> ADD MYSQL SCREENSHOT HERE

## Query Output

> ADD QUERY RESULT SCREENSHOT HERE

## Power BI Dashboard

> ADD DASHBOARD IMAGE HERE

---

# How to Run This Project

## Step 1: Import Dataset into MySQL

Import the CSV dataset into MySQL Workbench.

## Step 2: Create Database & Table

Run the `schema.sql` file.

## Step 3: Perform Data Cleaning

Execute `data_cleaning.sql`.

## Step 4: Run SQL Analysis

Run:
- exploratory_analysis.sql
- kpi_queries.sql
- advanced_queries.sql

## Step 5: Build Dashboard in Power BI

Connect MySQL database with Power BI and create visualizations.

---

# Future Improvements

- Add machine learning prediction model
- Create healthcare cost forecasting dashboard
- Integrate larger healthcare datasets
- Add stored procedures & triggers
- Build interactive web dashboard

---

# Dataset Source

Dataset collected from Kaggle for educational and portfolio purposes.

---

# Author

Abhishek Kalkhandey

Aspiring Healthcare Data Analyst | SQL | Power BI | Python

Dashborad ScreenShot -https://drive.google.com/file/d/11SyPbgHA6YBbtwLChBTEo6PFz1aRt7xR/view?usp=sharing
