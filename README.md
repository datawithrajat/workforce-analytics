# Workforce Analytics: Understanding Employee Turnover

![Python](https://img.shields.io/badge/Python-Analytics-blue?style=for-the-badge&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange?style=for-the-badge)
![Statistics](https://img.shields.io/badge/Statistical-Testing-green?style=for-the-badge)
![Project](https://img.shields.io/badge/Project-HR%20Analytics-success?style=for-the-badge)

---

# Project Overview

This project focuses on analyzing employee behavior, workforce engagement, compensation patterns, overtime participation, and organizational factors influencing employee attrition.

The analysis was performed using the **IBM HR Analytics Employee Attrition Dataset** with the objective of identifying meaningful workforce insights using:

- Descriptive Analytics
- Statistical Hypothesis Testing
- Predictive Modeling

The project demonstrates how workforce analytics and machine learning techniques can support employee retention strategies and organizational decision-making.

---

# Business Problem

Employee attrition creates major organizational challenges including:
- increased hiring costs,
- workforce instability,
- productivity loss,
- and employee replacement overhead.

The objective of this project was to identify:
- factors influencing attrition,
- workforce behavior patterns,
- and statistically significant retention drivers.

---

# Project Objectives

The primary objectives of this project were to:

- Analyze employee attrition behavior
- Identify workforce factors affecting employee turnover
- Understand overtime participation patterns
- Analyze salary and stock option distribution
- Validate assumptions using statistical testing
- Build a predictive model for employee attrition

---

# Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data Analysis |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| SciPy | Hypothesis Testing |
| Scikit-Learn | Machine Learning |
| Jupyter Notebook | Development Environment |

---

# Dataset Information

Dataset Used:
## IBM HR Analytics Employee Attrition Dataset

The dataset contains workforce-related information including:
- employee demographics,
- compensation,
- job roles,
- overtime participation,
- satisfaction metrics,
- work-life balance,
- stock options,
- and attrition behavior.

---

# Key Business Questions

## Workforce & Overtime Analysis
- What percentage of employees work overtime?
- Which job roles demonstrate the highest overtime participation?
- Does overtime participation differ across departments?
- Do high salary roles also demonstrate high overtime participation?

---

## Salary & Compensation Analysis
- Which job roles receive the highest average monthly income?
- Does compensation align with organizational hierarchy?
- Which roles receive lower compensation despite workload involvement?

---

## Stock Option Analysis
- Which departments receive the highest stock option levels?
- Which job roles receive the highest stock options?
- Does stock option distribution reflect organizational hierarchy?

---

## Attrition Analysis
- What percentage of employees leave the organization?
- Which departments demonstrate the highest attrition?
- Which job roles experience the highest attrition percentage?
- Are lower job levels more likely to leave the organization?

---

## Statistical Testing Questions
- Does overtime participation significantly influence attrition?
- Does work-life balance affect employee retention?
- Does job satisfaction influence attrition?
- Does job involvement affect retention?
- Does marital status influence attrition?
- Do salary hike and promotion timing significantly influence attrition?

---

# Project Workflow

```text
Data Preparation
       ↓
Descriptive Analytics
       ↓
Attrition Analysis
       ↓
Hypothesis Testing
       ↓
Predictive Modeling
       ↓
Business Insights
```

---

# Data Preparation

Performed:
- Data loading
- Table merging
- Data cleaning
- Feature preparation
- Dataset transformation

Multiple HR-related tables were merged to create analytical and predictive datasets.

---

# Descriptive Workforce Analytics

Performed workforce analysis on:
- employee overtime participation,
- salary distribution,
- stock option allocation,
- department-level workforce patterns,
- job-role compensation trends,
- and attrition behavior.

---

# Visualizations

## Employee Overtime Distribution

![Employee Overtime Distribution](Employee%20overtime%20distibution.jpg)

---

## Percentage of Employees Working Overtime

![Percentage of Employees Overtime](Percentage%20of%20employees%20Overtime.jpg)

---

## Job Roles Working Overtime

![Job Roles Working Overtime](Job%20Roles%20Working%20Overtime.jpg)

---

## Average Monthly Income

![Average Monthly Income](Average%20Monthly%20Income.jpg)

---

## Salary and Overtime Comparison

![Salary and Overtime Comparison](Salary%20and%20OverTime%20Comparision.jpg)

---

## Attrition Percentage by Department

![Attrition Percentage by Department](Attrition%20Percantage%20By%20Department.jpg)

---

## Attrition Percentage by Job Role

![Attrition Percentage by Job Role](Attrition%20Percantage%20by%20job%20rol.jpg)

---

## Attrition Percentage by Job Level

![Attrition Percentage by Job Level](Attrition%20Percantage%20by%20job%20level.jpg)

---

# Key Descriptive Insights

- Overtime participation was comparatively high across several operational job roles.
- Lower job levels demonstrated higher attrition percentages.
- Sales and Research-related departments demonstrated higher workforce turnover.
- Compensation and stock option distribution generally aligned with organizational hierarchy.

---

# Statistical Hypothesis Testing

Applied:
- Chi-Square Test of Independence
- Independent T-Test

to validate workforce assumptions statistically.

---

# Significant Factors Identified

The following variables demonstrated statistically significant relationships with employee attrition:

| Factor | Statistical Result |
|---|---|
| OverTime | Significant |
| JobSatisfaction | Significant |
| WorkLifeBalance | Significant |
| JobInvolvement | Significant |
| MaritalStatus | Significant |

---

# Non-Significant Factors

| Factor | Statistical Result |
|---|---|
| PercentSalaryHike | Not Significant |
| YearsSinceLastPromotion | Not Significant |

---

# Hypothesis Testing Summary

![Hypothesis Testing Summary](Hypothesis%20Testing%20Summary.jpg)

---

# Statistical Insights

The statistical analysis suggested that:
- employee workload pressure,
- work-life imbalance,
- employee engagement,
- and workplace satisfaction

demonstrate meaningful influence on workforce retention behavior.

OverTime demonstrated one of the strongest relationships with attrition.

In contrast:
- salary hike percentage,
- and promotion timing

did not independently demonstrate statistically significant relationships with attrition.

---

# Predictive Modeling

## Logistic Regression Model

A Logistic Regression model was developed to predict employee attrition behavior using workforce-related features such as:

- OverTime
- JobSatisfaction
- WorkLifeBalance
- JobInvolvement
- PercentSalaryHike
- MaritalStatus

---

# Model Performance

## Logistic Regression Accuracy
# 86%

The model demonstrated strong capability in predicting employee retention behavior.

---

# Confusion Matrix Heatmap

![Confusion Matrix Heatmap](Confusion%20Matrix%20Heatmap.jpg)

---

# Confusion Matrix Interpretation

The model correctly predicted:
- employees who remained within the organization,
- and several attrition cases successfully.

However:
- some attrition employees were incorrectly classified as retained employees.

This behavior may result from:
## Class Imbalance
where non-attrition employees significantly outnumber attrition employees.

---

# Final Project Conclusion

This project demonstrates how:
- workforce analytics,
- statistical validation,
- and machine learning techniques

can collectively support organizational decision-making and employee retention strategies.

The findings suggest that:
- employee experience,
- workplace engagement,
- work-life balance,
- organizational involvement,
- and workload-related pressure

play a more important role in workforce retention than compensation-growth variables alone.

The project successfully combines:
- descriptive analytics,
- business storytelling,
- statistical hypothesis testing,
- and predictive modeling

to create a comprehensive HR Analytics case study.

---

# Future Improvements

Potential future enhancements may include:
- advanced machine learning models,
- class balancing techniques,
- feature engineering,
- hyperparameter tuning,
- and interactive dashboards using Power BI or Streamlit.

---

# Author

## datawithRajat

### Data Analytics | Workforce Analytics | Statistical Analysis | Machine Learning

---
