# HR Analytics Capstone – Employee Attrition Analysis
**Dataset:** [HR Capstone Dataset](https://github.com/abhishek-s-shirol/HR_Analytics_Capstone/blob/main/HR_capstone_dataset.csv)
**Objective:** Understanding key factors influencing employee attrition at **Salifort Motors** and building a predictive model to enhance retention strategies.

## 📌 Project Overview  
Salifort Motors aims to improve employee satisfaction and reduce attrition rates. This project analyzes HR data to identify patterns contributing to employee turnover and proposes data-driven solutions for retention.

## 📊 Dataset Description
The dataset includes various features that provide insights into employee performance, workplace conditions, and satisfaction levels.

| Column Name | Description |
|-------------|------------|
| satisfaction_level | Employee-reported job satisfaction level (0–1) |
| last_evaluation | Performance review score (0–1) |
| number_project | Number of projects employee contributes to |
| average_monthly_hours | Average number of hours worked per month |
| time_spend_company | Years of experience in the company |
| Work_accident | Whether the employee experienced a workplace accident (1 = Yes, 0 = No) |
| left | Whether the employee left the company (1 = Yes, 0 = No) |
| promotion_last_5years | Whether the employee was promoted in the last 5 years (1 = Yes, 0 = No) |
| Department | Employee’s department |
| salary | Employee’s salary category (Low, Medium, High) |

## 🛠 Tools & Libraries Used
- **NumPy** – Data manipulation and numerical operations
- **Pandas** – Data wrangling and analysis
- **Seaborn** & **Matplotlib** – Data visualization
- **Scikit-learn** – Predictive modeling
  - Logistic Regression
  - Decision Tree
  - Random Forest

## 🔎 Analysis Approach
1. **Exploratory Data Analysis (EDA)** – Identifying trends in employee satisfaction, department attrition rates, and workload balance.
2. **Feature Engineering** – Preprocessing data, encoding categorical variables, and handling missing values.
3. **Predictive Modeling** – Training classification models to predict employee attrition.
4. **HR Recommendations** – Insights on how salary, promotions, and work-life balance affect retention strategies.

## 🔥 Key Insights & Recommendations
1. **Limit Employee Workload** – Cap the number of projects employees can work on to prevent burnout.
2. **Promotion & Career Growth** – Promote employees with at least four years at the company or investigate dissatisfaction at this tenure.
3. **Workload vs. Compensation** – Reward employees for longer hours or revise workload expectations.
4. **Transparency in Work Policies** – Inform employees about **overtime pay policies** and clarify workload expectations.
5. **Improving Workplace Culture** – Conduct **company-wide discussions** to address concerns about work culture.
6. **Performance Evaluations & Fairness** – Implement a **proportionate evaluation system** that fairly rewards all contributors, rather than favoring those working **200+ hours per month**.
