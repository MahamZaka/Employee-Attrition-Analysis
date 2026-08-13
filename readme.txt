# Employee Attrition Analysis Dashboard

## 📊 Project Overview

This project analyzes employee attrition data to identify key factors associated with employees leaving the organization. The analysis was performed using SQL for data exploration and Power BI for interactive dashboard visualization.

The goal of this project is to uncover patterns in employee attrition across departments, job roles, overtime, age groups, and years at the company.

---

## 🛠️ Tools & Technologies

- **PostgreSQL** – Data querying and analysis
- **Power BI** – Interactive dashboard and data visualization
- **SQL** – Data exploration and analysis
- **DAX** – Measures and calculated columns
- **Excel/CSV** – Data source

---

## 📁 Dataset

The dataset contains information about **1,470 employees** and includes employee demographics, job-related information, income, overtime, and attrition status.

Key columns include:

- Age
- Attrition
- Department
- JobRole
- Gender
- OverTime
- MonthlyIncome
- YearsAtCompany

---

## 🔍 Analysis Performed

The following analyses were performed using SQL:

- Overall employee attrition analysis
- Attrition rate by department
- Attrition rate by job role
- Attrition analysis based on overtime
- Comparison of monthly income between employees who stayed and employees who left
- Attrition analysis by age group
- Attrition analysis by years at the company
- Identification of high-risk employee groups

---

## 📈 Dashboard KPIs

The Power BI dashboard includes:

- **Total Employees**
- **Employees Left**
- **Attrition Rate**
- **Average Monthly Income**

Interactive slicers allow the dashboard to be filtered by:

- Department
- Gender

---

## 📊 Dashboard Visualizations

The dashboard includes the following visualizations:

- Employees Left by Department
- Employees Left by Job Role
- Employees Left by Overtime
- Employees Left by Age Group
- Employees Left by Tenure Group

---

## 💡 Key Insights

- The overall employee attrition rate is approximately **16.12%**.
- Employees working overtime show a higher number of employees leaving.
- Sales Representatives have the highest attrition rate among job roles.
- Younger employees, particularly those under 30, show higher attrition.
- Employees with **0–2 years** at the company have the highest attrition levels.
- Employees who left the company had a lower average monthly income compared with employees who stayed.
- Sales and Human Resources showed relatively higher attrition rates compared with Research & Development.

---

## 📂 Project Structure

```text
Employee-Attrition-Analysis/
│
├── Employee_Attrition_Analysis.pbix
├── employee_attrition.csv
└── README.md