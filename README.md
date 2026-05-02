# Workforce Risk & Value Dashboard

A Power BI HR analytics dashboard that helps identify top employees, flag retention risks, and evaluate workforce cost efficiency.

---

## What It Does

Answers three questions every HR team needs to know:
- Are we getting value for our salary spend?
- Who is most likely to leave?
- Where are our best people?

---

## Dataset

- 200 employees across 5 departments (Finance, HR, IT, Marketing, Sales)
- 11 columns: Name, Age, Gender, Department, Position, Joining Date, Salary, Projects Completed, Productivity, Satisfaction Rate, Feedback Score

---

## Metrics Built

| Metric | What It Measures |
|--------|-----------------|
| Productivity Efficiency Score (PES) | Output quality per project |
| Employee Value Index (EVI) | Overall employee contribution |
| Cost Per Productive Unit (CPPU) | Salary spend vs real output |
| Flight Risk Score (FRS) | Likelihood of leaving |
| Experience-Output Ratio (EOR) | Delivery rate per tenure year |
| Engagement Discord Score | Gap between satisfaction and feedback |
| Salary Equity Ratio | Pay fairness within peer groups |

---

## Dashboard Visuals

- KPI cards — 7 headline metrics at a glance
- Bar charts — PES and CPPU by department
- Column charts — EVI by position, Discord by department
- Bar chart — EOR by tenure band
- Scatter chart — Retention Risk Map (FRS vs EVI per employee)
- Slicers — filter by Department, Position, Tenure Band, Age

---

## Tools Used

- Power BI Desktop
- Power Query — data cleaning and segmentation
- DAX — all 7 custom measures

---

## How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Use the slicers on the right to filter by department, position or tenure
4. Focus on the Retention Risk Map — top-left quadrant = highest priority employees to retain

---

## Key Insight

> Marketing has the highest cost per productive unit at $895 — nearly 4x IT at $242. IT is the most efficient and lowest flight risk department.
