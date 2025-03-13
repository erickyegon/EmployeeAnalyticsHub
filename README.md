# EmployeeAnalyticsHub

# EmployeeAnalyticsHub

![Employee Overview Dashboard](screenshots/page1.png)

**EmployeeAnalyticsHub** is an advanced workforce analytics portfolio project that harnesses MySQL and Power BI to deliver deep insights into employee demographics, tenure, diversity, and predictive trends. Designed to showcase expertise in SQL query development and interactive data visualization, this project provides a comprehensive analysis of an employee dataset, offering actionable insights for HR decision-making.

---

## Project Overview

This repository encapsulates a robust analytics solution built around an employee dataset (`employees.csv`), featuring fields such as `id`, `first_name`, `last_name`, `birthdate`, `gender`, `race`, `department`, `jobtitle`, `location`, `hire_date`, `termdate`, `location_city`, and `location_state`. The project includes:

- **20 MySQL Queries**: From basic aggregations to advanced window functions and optimization techniques.
- **4-Page Power BI Dashboard**: Interactive visuals covering demographics, hiring trends, diversity, and predictive analytics.
- **Key Insights**: Detailed findings on workforce composition, retention, and geographic distribution.

Developed as a portfolio piece, this project demonstrates proficiency in MySQL for data manipulation and Power BI for business intelligence, tailored to HR analytics use cases.

---

## Key Features

- **Advanced MySQL Queries**: 20 scripts spanning demographics, tenure, advanced analytics, and performance optimization.
- **Interactive Power BI Dashboard**: Four detailed pages with slicers, charts, and predictive models.
- **Insight-Driven**: Uncovers trends in gender balance, racial diversity, age distribution, and more.
- **Portfolio-Ready**: Professional design and documentation for showcasing technical skills.

---

## Tech Stack

- **MySQL**: Query engine for data analysis and optimization.
- **Power BI Desktop**: Visualization tool for dashboard creation (March 2025 version).
- **Dataset**: Employee records in CSV format.
- **Git**: Version control for repository management.

---

## Repository Structure

```plaintext
EmployeeAnalyticsHub/
├── README.md              # Project documentation
├── sql/                   # MySQL scripts
│   ├── demographics.sql   # Demographics queries (Q1-Q5)
│   ├── tenure.sql        # Tenure and retention queries (Q6-Q10)
│   ├── advanced.sql      # Advanced analytics queries (Q11-Q15)
│   └── optimization.sql  # Performance optimization queries (Q16-Q20)
├── powerbi/              # Power BI dashboard file
│   └── EmployeeAnalyticsHub.pbix
├── data/                 # Sample dataset
│   └── employees_sample.csv
└── screenshots/          # Dashboard visuals
    ├── page1.png         # Employee Overview & Demographics
    ├── page2.png         # Hiring & Attrition Trends
    ├── page3.png         # Diversity & Inclusion
    └── page4.png         # Predictive Analytics
```

---

## Employee Insights & Highlights

### Overview
This project analyzes employee demographics using a sample dataset (`employees_sample.csv`). The insights below focus on *Page 1: Employee Overview & Demographics* and are scalable to larger datasets.

### Page 1: Employee Overview & Demographics

#### Total Number of Employees (Q1)
- **Insight**: "As of March 13, 2025, the workforce consists of 2 employees, providing a foundation for analysis that scales to [X] with full data."
- **Sample**: 2 employees (Kimmy and Ignatius).

#### Gender Distribution Across the Workforce (Q2)
- **Insight**: "Currently 100% male, reflecting the sample size; with broader data, expect a mix (e.g., 60% male, 40% female), highlighting gender representation trends."
- **Sample**: 2 males, 0 females.

#### Race/Ethnicity Breakdown by Department (Q3)
- **Insight**: "The sample shows a 50% Hispanic or Latino and 50% White split across Engineering and Business Development, suggesting early diversity that could expand to [X]% [Race] in [Department] with more data."
- **Sample**: 1 Hispanic or Latino (Engineering), 1 White (Business Development).

#### Age Distribution of Employees (Q4)
- **Insight**: "Employees are aged 33-34 in the sample, indicating a young workforce; expect a range of 25-65 with a peak at [X-Y] years in a full dataset."
- **Sample**: Kimmy (34), Ignatius (33).

#### Geographic Spread by State & City (Q18)
- **Insight**: "100% of employees are located in Cleveland, Ohio, suggesting a centralized hub; additional data may reveal [X]% distribution across [other states/cities]."
- **Sample**: 2 employees in Cleveland, Ohio.

#### Visual Representation
[Include Power BI screenshots or charts here]

---

### Notes
- This analysis is based on a small sample and will become more robust as data volume increases.
- Further pages in the dashboard will explore additional aspects such as tenure, job roles, and salary trends.
