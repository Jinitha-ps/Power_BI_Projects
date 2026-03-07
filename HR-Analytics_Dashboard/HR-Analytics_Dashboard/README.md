# 🧑‍💻 HR Analytics Dashboard Using Power BI

## 🚀 Project Overview

This project delivers an interactive **HR Analytics Dashboard** built using **Microsoft Power BI**. The goal is to transform raw employee data (provided in **`HR_Analytics.csv`**) into actionable insights, primarily focusing on **Employee Attrition**, **Workforce Engagement**, and **Performance Management**.

The dashboard serves as a single source of truth for HR and Management teams, facilitating data-driven decision-making to improve employee retention and optimize human capital.

---

## 🎯 Key Objectives & Analytical Focus

The analysis is structured to answer critical business questions and visualize key HR metrics:

| Focus Area | Key Metrics & Insights | Icon |
| :--- | :--- | :---: |
| **Attrition Risk** | Overall Attrition Rate, Departmental Attrition Hotspots, Years at Company vs. Attrition. | 📉 |
| **Engagement** | Job Satisfaction, Environment Satisfaction, and Work-Life Balance scores. | 🤝 |
| **Compensation** | Average Monthly Income by Job Role, Salary distribution, and relation to Performance Rating. | 💰 |
| **Demographics** | Headcount distribution by Age Group, Gender, and Education Field. | 👤 |
| **Performance** | Distribution of Performance Ratings and correlation with Percent Salary Hike. | ⭐ |

---

## 💾 Data Source & Preparation

The project utilizes the **`HR_Analytics.csv`** file.

### Data Attributes
The dataset is rich with over 30 attributes, including:
* `Attrition` (Target Variable: Yes/No)
* `Department`, `JobRole`, `JobLevel`
* `MonthlyIncome`, `PercentSalaryHike`
* `TotalWorkingYears`, `YearsAtCompany`
* `JobSatisfaction`, `WorkLifeBalance`

### 🔧 Data Modeling and Transformation
Power BI's **Power Query Editor** was used for the following preparation steps:
1.  **Data Cleaning:** Handling nulls and correcting data types.
2.  **Feature Engineering:** Creating calculated columns like `AgeGroup` and `SalarySlab` for better segmentation.
3.  **DAX Calculations:** Implementing complex measures for metrics like `Attrition Rate (%)` and `Average Satisfaction Score`.

---

## ✨ Dashboard Highlights

The final Power BI report features a modern, clean design, inspired by the provided visual references, offering an intuitive user experience with slicers and cross-filtering capabilities.

* **KPI Cards:** Prominent display of key performance indicators (e.g., Total Employees, Attrition Rate, Average Monthly Income).
* **Visualizations:** Use of bar charts (for departmental comparison), donut charts (for categorical breakdown), and scatter plots (for correlation analysis).
* **Interactivity:** Users can drill down into specific departments, job roles, or age groups to investigate trends.

---

## 🛠️ Technology Stack

* **Business Intelligence:** **Microsoft Power BI Desktop**
* **Data Source:** CSV File (`HR_Analytics.csv`)
* **Version Control:** Git

***
