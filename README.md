# U.S. Median Household Income 2015 Analysis

## Overview
I cleaned and analyzed U.S. median household income data from 2015. I focus on missing values, city/state-level aggregation, and exploratory summaries of income patterns.

## Motivation
I used this project to practice careful cleaning, aggregation, and interpretation. Income data is a good example of how missing values and geographic grouping choices can affect conclusions.

## Dataset
- **Source:** Kaggle U.S. Median Household Income 2015 dataset.
- **File:** `data/MedianHouseholdIncome2015.csv`
- **Target variable:** I did not define a supervised target for this version.
- **Important features:** geographic location fields and median household income values.
- **Known limitations:** The dataset is from 2015 only and does not capture current income levels or changes over time.

## Methods
- I loaded the household income dataset.
- I cleaned missing or irregular values.
- I grouped data by state and city.
- I computed average and median income summaries.
- I visualized income distributions and geographic differences.

## Results
I treat this as a data cleaning and EDA project, so I focus on cleaned summaries rather than a model metric.

## Key Insights
- Missing values can meaningfully affect state-level summaries.
- Geographic aggregation choices matter for interpretation.
- Single-year income data should not be generalized to long-term trends.

## Limitations
- The dataset covers one year only.
- I do not adjust for cost of living or population.
- Missing values and city coverage may bias state-level comparisons.
- The analysis is descriptive and does not explain causes of income differences.

## How to Run
```bash
git clone https://github.com/BobbY-24/US-Median-Income-2015--Data-Cleaning-and-Analysis.git
cd US-Median-Income-2015--Data-Cleaning-and-Analysis
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebooks/us_median_income_2015_analysis.ipynb
```
