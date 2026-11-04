# 📊 HR Employee Attrition Analysis Dashboard | Databricks AI/BI

A comprehensive HR Analytics project built using **Databricks SQL and Databricks AI/BI Dashboards** to analyse employee attrition patterns, identify workforce trends, and support data-driven HR decision-making.

---

## 📌 Project Overview

This project focuses on analysing employee attrition across an organisation using historical HR data.

The dashboard provides actionable insights into employee turnover, department-wise attrition, geographic distribution, job satisfaction, work-life balance, overtime, and other factors influencing employee retention.

The analysis covers **4,996 employees across 8 departments and 8 geographic locations**, with historical data spanning from **2016 to 2024**.

The primary objective is to identify attrition patterns, understand potential reasons behind employee exits, and provide recommendations to improve employee retention.

---

## 🎯 Project Objectives

- Calculate the overall employee attrition rate.
- Identify departments with the highest employee turnover.
- Analyse attrition across different job roles and locations.
- Compare salary hike percentages of employees who left versus those who stayed.
- Understand the relationship between overtime and employee attrition.
- Analyse the impact of work-life balance and job satisfaction.
- Investigate delayed promotions and manager relationships.
- Identify key factors associated with employee turnover.
- Provide actionable recommendations for improving employee retention.

---

## 📈 Key Performance Indicators (KPIs)

The dashboard tracks the following key metrics:

| KPI | Value |
|---|---:|
| Total Employees | 4,996 |
| Active Employees | 4,250 |
| Active Employee Percentage | 85.07% |
| Total Attrition | 746 |
| Overall Attrition Rate | 14.93% |
| Average Employee Age | 40.6 Years |
| Departments Tracked | 8 |
| Geographic Locations | 8 Cities |

---

## 📊 Dashboard Features

### 1. Executive KPI Panel

- Total workforce and active employee count.
- Overall employee attrition count and percentage.
- Average employee age.
- Total departments and geographic locations.

### 2. Department Analysis

- Department-wise employee attrition.
- Comparison of attrition rates across departments.
- Identification of high-attrition departments.
- Department-level workforce analysis.

### 3. Geographic Analysis

- Location-wise employee attrition across 8 Indian cities.
- Comparison of employee retention rates.
- Identification of locations with higher employee turnover.
- Regional workforce trend analysis.

### 4. Job Role Analysis

- Attrition analysis across different job roles.
- Identification of high-turnover positions.
- Comparison of employee departures and attrition rates.
- Role-based employee retention insights.

### 5. Temporal Trend Analysis

- Monthly hiring and attrition trends.
- Historical workforce analysis from 2016 to 2024.
- Identification of unusual attrition patterns.
- Seasonal trend analysis.

### 6. Root Cause Analysis

- Attrition reason categorisation.
- Work-life balance analysis.
- Overtime and job satisfaction analysis.
- Manager relationship and stress-level analysis.
- Multi-factor attrition analysis.
- Attrition risk score analysis.

---

## 🔍 Key Business Findings

### 1. Departmental Attrition Analysis

**Departments with the highest reported attrition:**

| Department | Employees Left | Attrition Rate |
|---|---:|---:|
| Customer Support | 124 | 17.77% |
| Finance | 112 | 15.05% |
| Operations | 101 | 14.07% |
| IT | 101 | 14.51% |

**Key Insight:**

Customer Support has the highest reported attrition rate at 17.77%, indicating a need for focused employee retention strategies.

### 2. Geographic Attrition Analysis

**Attrition by work location:**

| Location | Employees Left | Attrition Rate |
|---|---:|---:|
| Pune | 108 | 17.25% |
| Kolkata | 102 | 14.98% |
| Noida | 92 | 15.06% |
| Delhi | 91 | 14.65% |
| Bangalore | 87 | 13.64% |
| Mumbai | 87 | 13.90% |

**Key Insight:**

Pune reports the highest attrition rate among the listed locations at 17.25%, suggesting a need to investigate location-specific employee retention challenges.

### 3. Job Role Attrition Analysis

**Top 10 job roles by employee departures:**

| Rank | Job Role | Employees Left | Attrition Rate |
|---:|---|---:|---:|
| 1 | Customer Success Manager | 71 | 19.24% |
| 2 | Support Executive | 55 | 15.54% |
| 3 | Operations Executive | 55 | 15.03% |
| 4 | Supply Chain Analyst | 48 | 13.01% |
| 5 | Accountant | 47 | 17.54% |
| 6 | Recruiter | 40 | 16.00% |
| 7 | Marketing Manager | 38 | 16.81% |
| 8 | Sales Executive | 36 | 14.23% |
| 9 | Sales Manager | 36 | 15.72% |
| 10 | HR Manager | 35 | 15.15% |

**Key Insight:**

Customer Success Managers have the highest reported attrition rate at 19.24%, with 71 employee departures.

This highlights the importance of reviewing workload, career development, compensation, and employee engagement in this role.

### 4. Root Cause Analysis

**Top 3 reported combinations of attrition drivers (stated as approximately 54% of departures):**

| Attrition Driver Combination | Employee Cases | Percentage of Attrition |
|---|---:|---:|
| Poor Work-Life Balance + Overtime + Low Job Satisfaction | 239 | 32.04% |
| Poor Work-Life Balance + Low Job Satisfaction + Manager Issues | 90 | 12.06% |
| Poor Work-Life Balance + Overtime + Manager Issues | 83 | 11.13% |

**Other significant factors:**

| Attrition Driver Combination | Employee Cases | Percentage |
|---|---:|---:|
| Overtime + Low Job Satisfaction + Manager Issues | 81 | 10.86% |
| Poor Work-Life Balance + Overtime + High Stress | 46 | 6.17% |
| Poor Work-Life Balance + Low Job Satisfaction + High Stress | 43 | 5.76% |

**Key Insight:**

Poor work-life balance, excessive overtime, low job satisfaction, and manager-related issues frequently appear together in the reported attrition patterns.

These factors should be investigated through employee feedback and retention initiatives.

### 5. Work-Life Balance Analysis

**Critical findings:**

| Work-Life Balance Segment | Attrition Rate |
|---|---:|
| Low Work-Life Balance (<2.5) | 28.25% |
| High Work-Life Balance (3.5–4) | 6.12% |

**Key Insight:**

Employees in the low work-life balance segment have approximately **4.6 times the attrition rate** of employees in the high work-life balance segment.

This indicates a strong association between work-life balance and employee retention.

### 6. Temporal Attrition Analysis

- Average hiring volume: approximately 40–45 employees per month.
- Monthly attrition volume: approximately 5–10 employees.
- Notable spike: January 2020 recorded 14 employee departures.
- Historical analysis covers 2016–2024.
- Attrition remained relatively stable across the reported historical period.

The January 2020 increase may warrant further investigation to understand the factors behind the unusual number of departures.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Databricks | Data analysis and cloud-based analytics platform |
| Databricks SQL | SQL-based data querying and analysis |
| SQL Warehouse | Compute resource for executing SQL queries |
| Databricks AI/BI | Interactive dashboard development |
| GitHub | Project version control and code hosting |

### SQL Concepts Applied

The project uses the following SQL concepts:

- SELECT and DISTINCT
- WHERE and ORDER BY
- Aggregate Functions: COUNT(), SUM(), AVG()
- GROUP BY and HAVING
- CASE WHEN Statements
- JOIN Operations
- Common Table Expressions (CTEs)
- Subqueries
- CAST and Data Type Conversion
- Date Functions
- Percentage Calculations
- Conditional Aggregations

---

## 🗂️ Dataset Overview

**Dataset Size:** 4,996 employee records.

**Historical Period:** 2016–2024.

**Employee Attributes:** 28+ fields covering employee demographics, employment information, performance, satisfaction, and engagement.

### Data Categories

| Category | Attributes |
|---|---|
| Demographics | Age, Gender, Education Level |
| Employment | Department, Job Role, Experience Years, Joining Date |
| Location | Work Location, Distance from Home |
| Compensation | Monthly Income, Salary Hike Percent |
| Performance | Performance Rating, Projects Handled, Training Hours |
| Engagement | Job Satisfaction, Work-Life Balance, Environment Satisfaction |
| Well-being | Stress Level, Overtime, Absenteeism Days |
| Career | Years Since Last Promotion, Relationship with Manager |
| Employee Outcome | Attrition Status, Attrition Reason, Attrition Risk Score |

---

## 💡 Business Recommendations

Based on the analysis, the following actions are recommended.

### Immediate Actions (0–3 Months)

**1. Improve Work-Life Balance**
- Introduce flexible working arrangements.
- Review excessive overtime requirements.
- Prioritise Customer Support and Finance departments.

**2. Customer Success Manager Retention**
- Conduct employee stay interviews.
- Review compensation and career progression opportunities.
- Introduce mentorship programmes.

**3. Pune Location Investigation**
- Conduct location-specific employee surveys.
- Review local compensation benchmarks.
- Investigate commuting and workplace challenges.

### Short-Term Initiatives (3–6 Months)

**4. Manager Effectiveness**
- Introduce management development programmes.
- Implement 360-degree feedback systems.
- Improve manager-employee communication.

**5. Overtime Management**
- Establish overtime monitoring and approval procedures.
- Set department-level overtime targets.
- Encourage healthy working hours.

**6. Job Satisfaction**
- Conduct role-specific satisfaction surveys.
- Implement regular employee feedback.
- Improve career development opportunities.

### Long-Term Strategies (6–12 Months)

**7. Predictive Retention Model**
- Use attrition risk scores for early intervention.
- Develop automated high-risk employee alerts.
- Implement personalised retention plans.

**8. Employee Wellness**
- Introduce wellness initiatives.
- Provide stress management resources.
- Create employee support systems.

**9. Compensation Review**
- Benchmark salaries against market standards.
- Review salary hike policies.
- Evaluate promotion timelines and pay equity.

**10. Department-Specific Interventions**
- Customer Support: Workload balancing and career progression.
- Finance: Process automation and work distribution.
- Operations: Resource allocation and operational efficiency.

---

## 🎯 Success Metrics

The following KPIs can be monitored to measure employee retention improvements.

| KPI | Target |
|---|---|
| Overall Attrition Rate | Below 10% |
| Average Work-Life Balance Score | Above 3.5 |
| Overtime Hours per Employee | 10% Reduction |
| Job Satisfaction Score | Above 4.0 |
| Manager Relationship Score | Above 4.0 |
| Department-Specific Attrition | Continuous Improvement |
| Time-to-Fill | Monitor Reduction |
| Cost per Hire vs Cost of Attrition | Monitor Improvement |

---

## 🚀 How to Access the Dashboard

1. Open the Databricks Workspace.
2. Navigate to the HR Analytics project.
3. Open `HR_Attrition_Dashboard`.
4. Use the available filters to explore attrition by department, location, and time period.
5. Review KPIs, trends, and employee attrition patterns.

---

## 🔄 Data Refresh

| Item | Details |
|---|---|
| Refresh Frequency | Daily |
| Last Updated | Real-time metrics |
| Historical Coverage | 2016–2024 |

---

## 📌 Key Business Questions Answered

This dashboard addresses the following HR business questions:

1. What is the overall employee attrition rate?
2. Which departments have the highest attrition?
3. Which job roles are most affected by attrition?
4. What is the average salary hike percentage of employees who left versus those who stayed?
5. Which locations have the highest employee attrition?
6. Which departments are experiencing overtime-driven attrition?
7. How does the combination of overtime and work-life balance affect attrition?
8. Which satisfaction segments contribute most to total attrition?
9. Does delayed promotion increase attrition risk?
10. Are poor manager relationships associated with high-stress work environments?

---

## 📁 Project Assets

- **SQL Analysis:** Databricks SQL queries covering employee attrition business questions.
- **AI/BI Dashboard:** Interactive HR Employee Attrition Analysis dashboard.
- **Documentation:** Project objectives, methodology, key findings, and recommendations.

---


Data Analytics | SQL | Databricks | Power BI | Excel

This project is part of my practical learning journey in Data Analytics, focusing on developing SQL skills and solving real-world business problems through data analysis.

---

## ⭐ Project Highlights

- Analysed 4,996 employee records.
- Covered 8 departments and 8 geographic locations.
- Developed 10 HR business analysis questions.
- Applied SQL aggregations, conditional logic, and analytical functions.
- Created an interactive Databricks AI/BI dashboard.
- Identified workforce trends and potential employee retention challenges.

**Thanks for visiting this project!**
