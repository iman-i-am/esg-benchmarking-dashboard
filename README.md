# esg-benchmarking-dashboard
ESG performance benchmarking analysis for 20 global companies | Python · SQL Server · Power BI

# ESG Company Benchmarking Dashboard

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![SQL Server](https://img.shields.io/badge/SQL%20Server-2022-red?logo=microsoftsqlserver)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Excel](https://img.shields.io/badge/Excel-Data%20Collection-green?logo=microsoftexcel)
![Status](https://img.shields.io/badge/Status-In%20Progress-orange)

---

## Overview
An end-to-end ESG benchmarking analysis comparing the environmental 
performance of global companies using real CDP climate disclosure data. 
This project covers the full analytics pipeline — from raw data collection 
through to an interactive Power BI dashboard — answering the question:

> **Which companies are leading and lagging on ESG performance, 
> and what is driving the gap?**

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Excel | Raw data collection and initial structuring |
| Python (pandas, matplotlib, seaborn) | Data cleaning, EDA, feature engineering |
| SQL Server | Database design, storage, analytical queries |
| Power BI | Interactive benchmarking dashboard |

---

## Data Source
- **Source:** CDP Climate Change Open Dataset
- **URL:** https://www.cdp.net/en/research/global-reports
- **Coverage:** [X] companies across [X] sectors and [X] countries
- **Years:** 2020 – 2023

---

## Project Structure

```
esg-benchmarking-dashboard/
│
├── data/
│   ├── raw/          # Original CDP download — unedited
│   └── clean/        # Cleaned and processed data
│
├── notebooks/        # Python cleaning and EDA notebooks
├── sql/              # SQL Server schema and query files  
├── dashboard/        # Power BI screenshots and shareable link
├── reports/          # Key findings summary
└── README.md
```

---

## Key Metrics
- Scope 1 & 2 emissions (tonnes CO2e)
- Emissions intensity (per $1M revenue)
- Year-on-year emissions change (%)
- Sector-level benchmarks and peer comparison
- Emissions reduction targets vs actual performance

---

## Key Findings
> *To be updated as analysis is completed*

- 🔍 Finding 1
- 🔍 Finding 2
- 🔍 Finding 3

---

## Dashboard Preview
> *Screenshots to be added on completion*

---

## How to Reproduce
1. Clone this repository
2. Open `notebooks/01_data_cleaning.ipynb` in Google Colab
3. Upload `data/raw/cdp_data.csv` when prompted
4. Run all cells in order
5. Connect `data/clean/esg_clean.csv` to Power BI Desktop

---

## Project Progress

- [x] Repo setup and folder structure  
- [ ] Data collection and Excel structuring  
- [ ] Python data cleaning notebook  
- [ ] Exploratory data analysis notebook  
- [ ] SQL Server schema and analytical queries  
- [ ] Power BI dashboard (4 pages)  
- [ ] Key findings write-up  

---

## Author
**Iman Morongwa Ngwepe** — Research Data Analyst  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/imanmorongwa-ngwepe)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/[your-username])
