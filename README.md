# Quality-Analysis-Report

📌 Project Overview
This Power BI report provides a comprehensive Quality Performance Analysis across departments, managers, employees, and office locations. It is designed to help leadership identify operational bottlenecks, monitor defect and error trends, and evaluate auditor performance.

The dashboard consolidates multiple datasets — including sampling data, defect logs, error tracking, employee details, and calendar information — into a unified analytical view.

🎯 Objectives
Measure overall quality score across the organization

Track defects % and errors % over time

Compare performance by department, manager, employee, and location

Identify high‑risk areas with elevated defect or error rates

Provide actionable insights for process improvement and training focus

📊 Key Features
1. KPI Summary Cards
All Task Total

Sample Total & Sample %

Defects Total & Defects %

Errors Total & Errors %

Overall Quality Score

These KPIs provide an immediate snapshot of operational health.

2. Monthly Trend Analysis
Defects % vs Errors % (side‑by‑side comparison)

Errors % by Month (isolated trend)

This helps identify seasonal patterns, workflow issues, or training gaps.

3. Multi‑Dimensional Quality Breakdown
By Department
Shows how Backoffice, Finance, and Sales differ in quality performance.

By Office Location
Highlights geographic variations (e.g., Australia outperforming other regions).

By Manager
Identifies leadership impact on quality outcomes.

By Employee
Pinpoints individual performance strengths and weaknesses.

4. Bubble Chart — Sampling vs Defects vs Errors
A multi‑variable visualization showing how sampling volume correlates with defect and error rates.

5. Interactive Filters
Users can slice the report by:

Department

Auditor Name

Manager

Office Location

This enables targeted root‑cause analysis.

🧱 Data Model
The report uses a star‑schema‑style model with the following tables:

Data Sampling (fact)

Auditor Details (dimension)

Employee Details (dimension)

Calendar (dimension)

Office Location (dimension)

Relationships are built on employee ID, auditor ID, and date fields.

🔍 Insights & Findings
Quality score averages around 81%, with notable variation across managers and locations.

Defects % tends to be 2–3× higher than Errors %, indicating process issues rather than isolated mistakes.

Certain managers (e.g., Diana Mark, Nicholas Justin) consistently outperform others.

Employees show wide variance, suggesting opportunities for targeted coaching.

Australia has the strongest quality performance; UK and US show higher defect rates.

🛠️ Tools & Technologies
Power BI Desktop

DAX Measures

Data Modeling (Star Schema)

Interactive Visuals & Filters

Operational Quality Analytics
