# Quality-Analysis-Report

📌 Project Overview
This Power BI report provides a comprehensive Quality Performance Analysis across departments, managers, employees, and office locations. It is designed to help leadership identify operational bottlenecks, monitor defect and error trends, and evaluate auditor performance.

The dashboard consolidates multiple datasets — including sampling data, defect logs, error tracking, employee details, and calendar information — into a unified analytical view.

🎯 Objectives
Measure overall quality score across the organization

- Track defects % and errors % over time

- Compare performance by department, manager, employee, and location

- Identify high‑risk areas with elevated defect or error rates

- Provide actionable insights for process improvement and training focus

📊 Key Features
1. KPI Summary Cards
- All Task Total
- Sample Total & Sample %
- Defects Total & Defects %
- Errors Total & Errors %
- Overall Quality Score

**These KPIs provide an immediate snapshot of operational health.**

<img width="415" height="621" alt="DQA_PBI_p1" src="https://github.com/user-attachments/assets/6af9ea69-004d-49c5-bea8-0c656e6aa702" />

2. Monthly Trend Analysis
- Defects % vs Errors % (side‑by‑side comparison)
- Errors % by Month (isolated trend)

**This helps identify seasonal patterns, workflow issues, or training gaps.**
  
<img width="877" height="626" alt="DQA_PBI_P2" src="https://github.com/user-attachments/assets/a2551681-60e6-4e45-a634-3716c515545b" />


3. Multi‑Dimensional Quality Breakdown
- By Department
  Shows how Backoffice, Finance, and Sales differ in quality performance.
- By Office Location
  Highlights geographic variations (e.g., Australia outperforming other regions).
- By Manager
  Identifies leadership impact on quality outcomes.
- By Employee
  Pinpoints individual performance strengths and weaknesses.

  <img width="541" height="697" alt="DQA_PBI_p3" src="https://github.com/user-attachments/assets/59294d0f-aa51-42ec-a080-e1c314d17d5a" />

  <img width="430" height="217" alt="DQA_PBI_p4" src="https://github.com/user-attachments/assets/e9b3659f-7f2f-4e7f-974e-bbac0ffa36cb" />



4. Bubble Chart — Sampling vs Defects vs Errors
**A multi‑variable visualization showing how sampling volume correlates with defect and error rates.**

<img width="770" height="311" alt="DQA_PBI_p5" src="https://github.com/user-attachments/assets/0a3207d6-ae88-478d-b406-cd62e9fef5e2" />


6. Interactive Filters
Users can slice the report by:
- Department
- Auditor Name
- Manager

**This enables targeted root‑cause analysis.**

<img width="1297" height="107" alt="DQA_PBI_p6" src="https://github.com/user-attachments/assets/c46d324e-9bfb-4ab5-ae12-5418a638b620" />


🧱 Data Model
The report uses a star‑schema‑style model with the following tables:
- Data Sampling (fact)
- Auditor Details (dimension)
- Employee Details (dimension)
- Calendar (dimension)
- Office Location (dimension)

**Relationships are built on employee ID, auditor ID, and date fields.**

🔍 Insights & Findings
- Quality score averages around 81%, with notable variation across managers and locations.
- Defects % tends to be 2–3× higher than Errors %, indicating process issues rather than isolated mistakes.
- Certain managers (e.g., Diana Mark, Nicholas Justin) consistently outperform others.
- Employees show wide variance, suggesting opportunities for targeted coaching.
- Australia has the strongest quality performance; UK and US show higher defect rates.

🛠️ Tools & Technologies
- Power BI Desktop
- DAX Measures
- Data Modeling (Star Schema)
- Interactive Visuals & Filters
- Operational Quality Analytics

# Overview Page
<img width="1307" height="736" alt="DQA_PBI_p7" src="https://github.com/user-attachments/assets/d6411bc4-e58a-430b-a032-b29b2d435d91" />

# Details Page
<img width="1312" height="690" alt="DQA_PBI_p8" src="https://github.com/user-attachments/assets/b835726b-a5c8-4a7e-a828-4973cf8207ae" />

# Overview Analysis Page
<img width="1301" height="730" alt="DQA_PBI_p9" src="https://github.com/user-attachments/assets/7ff2985d-5de2-4023-ad57-19b2e302b9cc" />



