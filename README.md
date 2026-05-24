# Workforce Analytics: Understanding Employee Turnover

![Python](https://img.shields.io/badge/Python-Analytics-blue?style=for-the-badge&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange?style=for-the-badge)
![Statistics](https://img.shields.io/badge/Statistical-Testing-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

---

# Project Overview

This project focuses on analyzing employee behavior, workplace experience, compensation patterns, and organizational factors influencing employee attrition within an organization.

The analysis was performed using the IBM HR Analytics Employee Attrition dataset with the objective of identifying meaningful workforce insights through:

- Descriptive Analytics
- Statistical Hypothesis Testing
- Predictive Modeling

The project demonstrates how workforce analytics and machine learning can support employee retention strategies and organizational decision-making.

---

# Project Objectives

The primary objectives of this project were to:

- Analyze employee attrition behavior
- Identify workforce factors affecting employee turnover
- Validate workforce assumptions using statistical testing
- Build a predictive model for employee attrition
- Understand workforce retention patterns

---

# Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data Analysis & Modeling |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Visualization |
| Seaborn | Statistical Visualization |
| SciPy | Hypothesis Testing |
| Scikit-Learn | Machine Learning |
| Jupyter Notebook | Development Environment |

---

# Dataset Information

Dataset Used:
## IBM HR Analytics Employee Attrition Dataset

The dataset contains workforce-related information including:

- Employee demographics
- Compensation information
- Job roles
- Overtime participation
- Satisfaction metrics
- Work-life balance
- Attrition status

---

# Key Business Questions

## Workforce & Overtime Analysis
- What percentage of employees work overtime?
- Which job roles demonstrate the highest overtime participation?
- Does overtime participation differ across departments?
- Do high-salary job roles also demonstrate high overtime participation?

---

## Salary & Compensation Analysis
- Which job roles receive the highest average monthly income?
- Does compensation align with organizational hierarchy?
- Which job roles receive comparatively lower compensation despite workload involvement?

---

## Stock Option Analysis
- Which departments receive the highest stock option levels?
- Which job roles receive the highest stock options?
- Does stock option distribution reflect organizational hierarchy?

---

## Attrition Analysis
- Which departments demonstrate the highest attrition?
- Which job roles experience the highest attrition?
- Are lower job levels more likely to leave the organization?

---

## Hypothesis Testing Questions
- Does overtime participation significantly influence attrition?
- Does work-life balance affect employee retention?
- Does job satisfaction influence attrition?
- Does job involvement affect employee retention?
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

# Descriptive Workforce Analytics

Performed workforce analysis on:

- Employee overtime participation
- Salary distribution
- Stock option allocation
- Department-level workforce patterns
- Job-role compensation trends
- Attrition behavior

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

## Hypothesis Testing Summary

![Hypothesis Testing Summary](Hypothesis%20Testing%20Summary.jpg)

---

## Confusion Matrix Heatmap

![Confusion Matrix Heatmap](Confusion%20Matrix%20Heatmap.jpg)

---

# Statistical Hypothesis Testing

Applied:
- Chi-Square Test of Independence
- Independent T-Test

to validate workforce assumptions statistically.

---

# Significant Factors Identified

The following variables demonstrated statistically significant relationships with employee attrition:

| Factor | Result |
|---|---|
| OverTime | Significant |
| JobSatisfaction | Significant |
| WorkLifeBalance | Significant |
| JobInvolvement | Significant |
| MaritalStatus | Significant |

---

# Non-Significant Factors

| Factor | Result |
|---|---|
| PercentSalaryHike | Not Significant |
| YearsSinceLastPromotion | Not Significant |

---

# Hypothesis Testing Summary

![Hypothesis Testing Summary](visuals/hypothesis_testing_summary.jpg)

---

# Key Statistical Insights

- Overtime participation demonstrated one of the strongest relationships with attrition.
- Employees with lower work-life balance and lower job satisfaction showed higher attrition behavior.
- Job involvement significantly influenced workforce retention.
- Single employees demonstrated comparatively higher attrition levels.
- Compensation-growth variables alone did not strongly explain workforce attrition behavior.

---

# Predictive Modeling

## Logistic Regression Model

A Logistic Regression model was developed to predict employee attrition behavior using:

- Overtime participation
- Job Satisfaction
- Work-Life Balance
- Job Involvement
- Salary Hike Percentage
- Marital Status

---

# Model Performance

## Logistic Regression Accuracy
# 86%

The model demonstrated strong capability in predicting employee retention behavior.

---

# Confusion Matrix Heatmap

![Confusion Matrix](visuals/confusion_matrix_heatmap.jpg)

---

# Confusion Matrix Interpretation

The model correctly predicted:
- 247 employees who stayed
- 6 employees who left

However:
- 33 attrition cases were missed
- indicating lower prediction capability for attrition employees.

This behavior may result from:
## Class Imbalance
where non-attrition employees significantly outnumber attrition employees.

---

# Final Conclusion

This project demonstrates how workforce analytics, statistical validation, and machine learning techniques can collectively support organizational decision-making and employee retention strategies.

The findings suggest that:

- Employee experience
- Workplace engagement
- Work-life balance
- Organizational involvement
- Workload-related pressure

play a more important role in workforce retention than compensation-growth factors alone.

The project successfully combines:

- Descriptive Analytics
- Business Storytelling
- Statistical Hypothesis Testing
- Predictive Modeling

to create a comprehensive HR Analytics case study.

---

# Future Improvements

Potential future enhancements may include:

- Advanced machine learning models
- Class balancing techniques
- Feature engineering
- Hyperparameter tuning
- Interactive dashboards using Power BI or Streamlit

---

# Author

## DatawithRajat

Data Analytics | Workforce Analytics | Statistical Analysis | Machine Learning

---
