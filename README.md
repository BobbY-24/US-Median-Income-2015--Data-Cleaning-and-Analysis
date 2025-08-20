📊 U.S. Median Household Income (2015) — Data Cleaning & Analysis
📌 Project Overview

This project analyzes U.S. median household income (2015) by state and city using a dataset from Kaggle. The workflow involves data cleaning, handling missing values, and computing state-level averages and medians.

The project highlights how missing values affect state-level data quality and provides insights into which states have the highest average and median incomes across their cities.

📂 Dataset

Source: Kaggle — Median Household Income (2015)

File: MedianHouseholdIncome2015.csv

Key Columns:

Geographic Area → State

City → City name

Median Income → Median household income

🛠️ Workflow
1. Data Loading & Exploration

Loaded dataset with latin-1 encoding.

Inspected sample rows and missing values.

2. Data Cleaning

Converted Median Income to numeric (errors='coerce').

Dropped invalid or NaN entries.

Verified dataset size before and after cleaning.

3. Missing Value Analysis

Counted records per state before vs. after cleaning.

Computed difference (NaN counts) and percentage of NaNs per state.

Visualized:

Pie chart → Distribution of NaN values across states.

Bar chart → Top 10 states with the highest missing value counts.

Bar chart → Top 10 states with the highest percentage of missing values.

4. State-Level Income Statistics

Grouped data by Geographic Area (state).

Computed:

Average city income per state.

Median city income per state.

Number of cities represented per state.

Visualized:

Top 10 states by average income.

Top 10 states by median income.

📊 Key Insights

Missing Data: 5,811 entries (~6.6%) had missing income values.

NaN Distribution: Missing values were unevenly distributed, with some states losing more city-level data than others.

High-Income States: Both average and median income analyses identified the states with the wealthiest cities (e.g., states with higher living costs such as California and New York).

Median vs. Average: Using both statistics allowed for a more robust comparison, since averages can be skewed by outliers.

📦 Tools & Libraries

pandas → Data wrangling, grouping, aggregation

numpy → Numeric handling

matplotlib / seaborn → Visualizations (bar charts, pie charts)

scikit-learn (StandardScaler, PCA) → Imported for potential extensions

🚀 Next Steps

Apply imputation methods (e.g., mean or regression-based filling) for missing values.

Extend analysis to regional comparisons (e.g., Northeast vs. South).

Use PCA or clustering to identify income distribution patterns across states.

Combine income data with other socio-economic indicators for deeper insights.
