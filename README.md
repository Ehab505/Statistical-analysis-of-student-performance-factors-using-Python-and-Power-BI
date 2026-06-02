# Student Performance Analysis

## Overview
A statistical analysis investigating which family background factors 
affect student academic performance, using a dataset of 395 students.

## Research Questions
1. Does parental job type affect student average score?
2. Is there a relationship between parental education and student scores?
3. Do rural students score higher than urban students?
4. Does family size affect student performance?
5. What factors jointly predict student average score?

## Methods
## Normality test
 - Shapiro test is used because the observaions is less than 200
## Homogeneity of variance 
- Levene's test is applied 
## for testing the claims
- Two-way ANCOVA (parental job analysis)
- Spearman rank correlation (parental education)
- Independent samples t-test (address and family size)
- OLS Multiple Linear Regression (predictive factors)

## Key Findings
- The interaction between mother and father job types 
  significantly affects scores (p = 0.04), independent 
  of education level
- Parental education shows a weak but significant positive 
  correlation with scores (ρ = 0.226, p < 0.001)
- Family size and address showed no significant effect 
  after correction

## Tools Used
- Python (pandas, scipy, statsmodels, sklearn)
- Power BI (interactive dashboard)
- Jupyter Notebook

## Files
| File | Description |
|---|---|
| notebook/Student_analyses_project.ipynb | Full analysis notebook |
| powerbi/student_performance_dashboard.pbix | Power BI dashboard |
| data/student_data_clean.csv | Cleaned dataset |

## Dashboard Preview
![Dashboard](dashboard_preview.png)
