# A Regression and Visualization Study of Data Science Job Market Trends

## 📊 Overview

This project investigates salary trends in the data science job market using the `jobs_in_data` dataset comprising over 10,000 entries. It explores the impact of variables like job title, company size, employment type, and experience level on salary—both in local and USD values. 

Our main goal is to use regression models and visualizations to analyze and predict salary patterns, providing insights for job seekers, employers, and policy-makers within the data industry.

## 👥 Authors

- Abdul Sameer Shaik  
- Deepashree Srinivasa Rao Rannore  
- Jeevith Doddalingegowda Rama  
- Sunidi Vijayakrishna Kumar  

## 🗃️ Dataset

The main dataset used:
- **Data Science Job Salaries** from Kaggle: [Link](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)

Supplementary data:
- Cost of Living and Income dataset (for adjusted salary analysis)

## 🛠️ Methodology

1. **Data Cleaning and Preprocessing**
   - Handled missing values using imputation
   - Encoded categorical variables via one-hot encoding
   - Standardized and normalized salary features
   - Removed outliers using IQR and Z-score techniques

2. **Exploratory Data Analysis (EDA)**
   - Visualizations: histograms, box plots, density plots
   - Correlation analysis between features
   - Salary distributions across job roles, experience levels, company size, and work settings

3. **Modeling**
   - Built and evaluated a linear regression model to predict salary
   - Performance measured using RMSE and R²
   - Identified key factors influencing salary

## 📈 Key Findings

- Senior roles and jobs at larger companies generally have higher salaries.
- Remote roles tend to offer competitive salaries, influenced by global hiring.
- Strong correlations were found between salary and experience level, job title, and company size.
- Salary trends show consistency or growth over the years 2020–2023.

## 🧰 Technologies Used

- **R**: RStudio, `ggplot2`, `dplyr`, `caret`, `lm()`, `stepAIC`, etc.
- **Visualization**: Box plots, density plots, correlation heatmaps, and regression diagnostics.

## 📂 Project Structure

```
📁 DataScience-Salary-Trends/
│
├── data/
│   ├── jobs_in_data.csv
│   └── Cost_of_Living_and_Income_Extended.csv
│
├── scripts/
│   ├── data_cleaning.R
│   ├── eda_visualizations.R
│   ├── regression_model.R
│   └── correlation_analysis.R
│
├── results/
│   └── plots/
│       ├── salary_distribution.png
│       ├── correlation_matrix.png
│       └── regression_diagnostics.png
│
├── A_Regression_and_Visualization_Study_of_Data_Science_Job_Market_Trends.pdf
├── README.md
└── .gitignore
```

## 🔍 References

1. [Kaggle Dataset](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)  
2. [IEEE Trends in Data Science Careers](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10859447)  
3. [SSRN - Tech Skills Impact on Salaries](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3526707)

## 📬 Contact

For any queries or contributions, feel free to reach out via GitHub or contact the contributors.
