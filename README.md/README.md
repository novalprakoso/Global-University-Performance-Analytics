# Global University Performance Analytics for Institutional Benchmarking

## Project Overview

This project analyzes global university ranking data from QS World University Rankings 2026, Times Higher Education (THE) 2026, and Academic Ranking of World Universities (ARWU) 2025.

The project demonstrates an end-to-end data analytics workflow, including data profiling, data cleaning, feature engineering, SQL analysis, and Power BI dashboard development to support institutional reporting and benchmarking.

---

## Business Context

Higher education institutions rely on accurate and reliable data to support institutional reporting, benchmarking, and strategic decision-making.

This project uses global university ranking data as a case study to demonstrate how data quality assessment and analytical techniques can transform raw institutional data into meaningful insights.

---

## Business Questions

This project aims to answer the following business questions:

1. Is the university ranking dataset complete, accurate, and reliable for reporting and analytical purposes?
2. What data quality issues need to be addressed before analysis?
3. How are universities distributed across countries, regions, and institution types?
4. What are the overall performance trends across the QS, THE, and ARWU ranking systems?
5. How can clean and validated data support institutional reporting and benchmarking?

---

## Business Objectives

This project aims to:

- Assess data quality through comprehensive data profiling.
- Validate institutional data against business rules.
- Prepare a clean dataset for SQL analysis and Power BI reporting.
- Analyze institutional performance using SQL.
- Generate insights for reporting and institutional benchmarking.

---

## Technology Stack

| Category | Tools |
|----------|-------|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib |
| Database | MySQL |
| Query Language | SQL |
| Business Intelligence | Power BI |
| Development | Jupyter Notebook, VS Code |

---

## Dataset Overview

| Item | Description |
|------|-------------|
| Universities | 57 |
| Countries | 20 |
| Regions | 7 |
| Ranking Systems | QS 2026, THE 2026, ARWU 2025 |
| Variables | 30 |

### Main Features

- University Information
- Global Rankings
- Research Indicators
- Internationalization Metrics
- Student Population
- Institutional Profile

---

## Project Workflow

```
Raw Dataset
      │
      ▼
Data Profiling
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
MySQL Database
      │
      ▼
SQL Analysis
      │
      ▼
Power BI Dashboard
```

---

## Repository Structure

```
global_university_performance_analytics/
│
├── data
│   ├── raw
│   ├── cleaned
│   └── featured
│
├── notebooks
│   ├── 01_data_profiling.ipynb
│   ├── 02_data_cleaning.ipynb
│   └── 03_feature_engineering.ipynb
│   └── 04_mysql_integration.ipynb
|
├── sql
│
├── powerbi
│
└── README.md
```

---

## Project Progress

| Stage | Status |
|--------|--------|
| Data Profiling | ✅ Completed |
| Data Cleaning | ✅ Completed |
| Feature Engineering | ✅ Completed |
| MySQL Integration | ✅ Completed |
| SQL Analysis | ✅ Completed |
| Power BI Dashboard | ⏳ Planned |

---

## Key Data Quality Findings

- No duplicate records detected.
- 98 missing values identified across 17 columns.
- Missing values are informative because not all universities appear in every ranking system.
- No invalid ranking scores or percentage values.
- No category inconsistencies were found.
- Detected outliers were reviewed and considered valid business observations.

---

## Feature Engineering

The following business-oriented features were created:

- Ranking System Count
- Top 100 Flags
- Student Size Group
- Internationalization Level
- Age Group
- Research Awards
- Research Level
- Ranking Category

---

## Next Development

- MySQL database implementation
- SQL analytical queries
- Interactive Power BI dashboard
- Business recommendations

---

## Author

**Noval Prakoso**

Data Analyst | SQL | Python | Power BI
