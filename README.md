# Databricks-HR-Employee-Attrition-Analysis

A comprehensive analytics dashboard for tracking and analyzing employee attrition patterns, built on Databricks AI/BI platform.
Overview
This dashboard provides actionable insights into employee turnover across the organization, enabling data-driven HR decision-making and proactive retention strategies. The analysis covers 4,996 employees across 8 departments and 8 geographic locations with historical data spanning from 2016 to 2024.
Key Metrics
Metric
Value
Total Employees
4,996
Active Employees
4,250 (85.07%)
Attrition Count
746
Attrition Rate
14.93%
Average Employee Age
40.6 years
Departments Tracked
8
Locations Tracked
8 cities
Dashboard Features
1. Executive KPI Panel
Real-time metrics for total workforce, active headcount, and attrition rates
Average employee age tracking
Department count overview
2. Department Analysis
Attrition breakdown by department with comparative rates
Identifies high-risk departments requiring intervention
Visual comparison of department performance
3. Geographic Insights
Location-wise attrition patterns across 8 Indian cities
City-specific retention rates
Regional trend analysis
4. Job Role Analysis
Role-based attrition tracking
Identification of high-turnover positions
Career path retention insights
5. Temporal Trends
Monthly hiring vs attrition tracking
Historical trend analysis (2016-2024)
Seasonal pattern identification
6. Root Cause Analysis
Detailed attrition reason categorization
Multi-factor analysis (work-life balance, overtime, job satisfaction, etc.)
Predictive risk scoring
Key Findings
Departmental Insights
Highest Attrition Departments:
Customer Support: 124 employees (17.77% rate)
Finance: 112 employees (15.05% rate)
Operations: 101 employees (14.07% rate)
IT: 101 employees (14.51% rate)
Customer Support shows the highest attrition rate, requiring immediate attention to retention strategies.
Geographic Distribution
Attrition by Location:
Pune: 108 employees (17.25% rate) - Highest
Kolkata: 102 employees (14.98% rate)
Noida: 92 employees (15.06% rate)
Delhi: 91 employees (14.65% rate)
Bangalore: 87 employees (13.64% rate) - Lowest
Mumbai: 87 employees (13.90% rate)
Pune location shows significantly higher attrition, suggesting location-specific challenges that need investigation.
High-Risk Job Roles
Top 10 Roles by Attrition:
Customer Success Manager: 71 departures (19.24% rate)
Support Executive: 55 departures (15.54% rate)
Operations Executive: 55 departures (15.03% rate)
Supply Chain Analyst: 48 departures (13.01% rate)
Accountant: 47 departures (17.54% rate)
Recruiter: 40 departures (16.00% rate)
Marketing Manager: 38 departures (16.81% rate)
Sales Executive: 36 departures (14.23% rate)
Sales Manager: 36 departures (15.72% rate)
HR Manager: 35 departures (15.15% rate)
Customer Success Managers face the highest attrition risk at nearly 1 in 5 employees.
Root Causes of Attrition
Top 3 Attrition Drivers (54% of all departures):
Poor Work-Life Balance + Overtime + Low Job Satisfaction
239 cases (32.04% of all attrition)
The single largest driver of employee turnover
Poor Work-Life Balance + Low Job Satisfaction + Manager Issues
90 cases (12.06% of all attrition)
Highlights importance of management quality
Poor Work-Life Balance + Overtime + Manager Issues
83 cases (11.13% of all attrition)
Combined operational and leadership challenges
Other Significant Factors:
Overtime + Low Job Satisfaction + Manager Issues: 81 cases (10.86%)
Poor Work-Life Balance + Overtime + High Stress: 46 cases (6.17%)
Poor Work-Life Balance + Low Job Satisfaction + High Stress: 43 cases (5.76%)
Work-Life Balance Impact
Critical Finding:
Low Work-Life Balance (<2.5 rating): 28.25% attrition rate
High Work-Life Balance (3.5-4 rating): 6.12% attrition rate
Impact: Employees with poor work-life balance are 4.6x more likely to leave
This represents the single strongest predictor of employee retention in the organization.
Temporal Patterns
Hiring Rate: Averages 40-45 employees per month with stable patterns
Attrition Rate: Consistent 5-10 employees per month
Notable Spike: January 2020 showed 14 departures (likely pandemic-related)
Trend: Relatively stable attrition over 8-year period
Technology Stack
Platform: Databricks AI/BI Dashboard
Data Source: HR employee database (4,996 records)
Visualization: Interactive charts, KPI cards, and trend analysis
Time Range: 2016-2024 (8+ years of historical data)
Data Points: 28+ employee attributes including demographics, performance, satisfaction, and engagement metrics
Data Schema
The dashboard tracks the following employee attributes:
Demographics: Age, Gender, Education Level
Employment: Department, Job Role, Experience Years, Joining Date
Location: Work Location, Distance from Home
Compensation: Monthly Income, Salary Hike Percent
Performance: Performance Rating, Projects Handled, Training Hours
Engagement: Job Satisfaction, Work-Life Balance, Environment Satisfaction
Well-being: Stress Level, Overtime, Absenteeism Days
Career: Years Since Last Promotion, Relationship with Manager
Outcome: Attrition Status, Attrition Reason, Attrition Risk Score
Actionable Recommendations
Immediate Actions (0-3 months)
Work-Life Balance Initiative
Implement flexible working arrangements
Review and reduce excessive overtime requirements
Target Customer Support and Finance departments first
Customer Success Manager Retention Program
Conduct stay interviews with current CSMs
Review compensation and career progression paths
Implement mentorship programs
Pune Location Investigation
Conduct location-specific employee surveys
Review local market compensation benchmarks
Address location-specific concerns (commute, facilities, etc.)
Short-Term Initiatives (3-6 months)
Manager Effectiveness Training
Develop management training programs
Implement 360-degree feedback systems
Focus on departments with high manager-related attrition
Overtime Management System
Establish overtime monitoring and approval processes
Set department-level overtime targets
Reward teams that maintain healthy work hours
Job Satisfaction Enhancement
Conduct role-specific satisfaction surveys
Implement regular feedback mechanisms
Create clear career development paths
Long-Term Strategy (6-12 months)
Predictive Retention Model
Leverage attrition risk scores for early intervention
Implement automated alerts for high-risk employees
Create personalized retention plans
Stress Reduction Programs
Launch wellness and mental health initiatives
Provide stress management resources
Create support systems for high-stress roles
Compensation Review
Benchmark salaries against market rates
Review salary hike policies and promotion timelines
Address pay equity concerns
Department-Specific Interventions
Customer Support: Workload balancing, career paths
Finance: Process automation, work distribution
Operations: Resource allocation, efficiency tools
Success Metrics
Track the following KPIs to measure retention improvement:
Overall attrition rate (target: <10%)
Department-specific attrition rates
Work-life balance scores (target: >3.5 average)
Overtime hours per employee (target: <10% reduction)
Job satisfaction scores (target: >4.0 average)
Manager relationship scores (target: >4.0 average)
Time-to-fill for critical roles
Cost per hire vs. cost of attrition
Usage
Accessing the Dashboard
Navigate to Databricks AI/BI workspace
Open HR_Attrition_Dashboard
Use filters to drill down by department, location, or time period
Key Questions the Dashboard Answers
What is our current attrition rate?
Which departments/locations/roles have the highest turnover?
What are the primary reasons employees leave?
How do hiring and attrition trends compare over time?
Which employees are at highest risk of leaving?
What factors most strongly predict attrition?
Data Refresh
Frequency: Daily
Last Updated: Real-time metrics
Historical Data: 2016-2024
Contributing
For questions, suggestions, or data access requests, please contact:
HR Analytics Team
People Operations Department
