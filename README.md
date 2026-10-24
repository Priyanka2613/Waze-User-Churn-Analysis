# Waze User Churn Analysis

## Project Overview
This project explores user churn and driving behavior using an educational Waze dataset from the Google Advanced Data Analytics Professional Certificate on Coursera.

The objective is to inspect data quality, investigate missing values, compare churned and retained users, and identify patterns that can guide future exploratory analysis.

## Tools and Skills
- Python
- Pandas and NumPy
- Jupyter Notebook
- Data inspection and cleaning assessment
- Descriptive statistics and grouped analysis
- User churn analysis

## Dataset Overview
- 14,999 user records
- 13 original columns
- 14,299 records with known churn labels
- 700 missing values in the `label` column (4.67%)
- Two labeled groups: `retained` and `churned`

## Key Findings

### 1. Missing Data
The `label` column contains 700 missing values. Device proportions among records with missing labels are similar to those in the full dataset, suggesting no obvious relationship between missing labels and device type. This does not establish that the data are missing completely at random.

### 2. User Retention and Churn
Among users with known labels:
- Retained: 11,763 users
- Churned: 2,536 users
- Approximately 82% retained and 18% churned

### 3. Driving Behavior

| Metric (Median) | Churned | Retained |
|---|---:|---:|
| Drives per driving day | 10.00 | 4.06 |
| Kilometers per driving day | 697.54 | 289.55 |
| Kilometers per drive | 74.11 | 75.01 |

Churned users made more trips and traveled farther on driving days, although the median distance per individual drive was slightly higher for retained users.

### 4. Device Usage
- Overall device distribution: 64.48% iPhone and 35.52% Android
- Churn rate among labeled iPhone users: approximately 17.83%
- Churn rate among labeled Android users: approximately 17.54%

Churn rates were similar across device types, suggesting that device choice alone may not be a useful indicator of churn.

## Business Insights
- Investigate whether frequent drivers have different navigation needs or app experiences.
- Explore feedback, satisfaction, and app performance data to understand potential drivers of churn.
- Examine missing churn labels before building predictive models.

## Project Scope and Limitations
This project focuses on preliminary data inspection and descriptive analysis. It does not build a churn prediction model or establish causal relationships. The dataset is provided for educational purposes and should not be interpreted as verified production Waze data.

## Project Notebook
[View the Jupyter Notebook](Activity_Course%202%20Waze%20project%20lab.ipynb)

## Next Steps
Further exploratory data analysis, data visualization, statistical testing, and predictive modeling could help evaluate the patterns identified in this notebook.

## Acknowledgment
Completed as part of the Google Advanced Data Analytics Professional Certificate on Coursera.
## Executive Summary

A one-page executive summary highlighting the project's key findings, user churn patterns, and recommended next steps.

[View Executive Summary (PDF)](https://github.com/Priyanka2613/Waze-User-Churn-Analysis/blob/main/Waze%20User%20Churn%20Analysis%20_%20Executive%20Summary.pdf)
