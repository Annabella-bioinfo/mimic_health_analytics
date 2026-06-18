# Patient Admissions and Outcomes Analysis
### MIMIC-IV Clinical Database Demo | Python | SQL | Power BI

## Project Overview
This project analyzes patient admissions data from Beth Israel Deaconess Medical 
Center using the MIMIC-IV Demo dataset. The goal is to identify patterns in 
admissions, length of stay, mortality, and readmissions to support clinical 
operations and resource planning decisions.

 
## Dataset
**Source:** MIMIC-IV Clinical Database Demo v2.2 (PhysioNet)
**Access:** Credentialed access via PhysioNet (CITI certified)
**Tables used:** patients, admissions, diagnoses_icd, d_icd_diagnosis
**Total admissions analyzed:** 275 admissions across 100 de-identified patients

## Tools Used
**Python** (pandas, matplotlib, seaborn) — data cleaning and EDA
**SQL** (SQLite via Python) — structured clinical queries
**Power BI** — interactive dashboard (see Project 2)
**Jupyter Notebook** — analysis environment

## Clinical Questions Answered
1. What are the most common admission types?
2. Which admission types have the longest average length of stay?
3. What is the in-hospital mortality rate by admission type?
4. What are the top 10 primary diagnoses driving admissions?
5. What is the 30-day readmission rate?

## Key Findings
Emergency walk-in admissions dominate volume at 38% of all cases. However, urgent 
admissions carry the highest mortality rate at 13.16% and the longest average stay 
at 9.85 days, signaling greater clinical complexity despite lower volume. The 
in-hospital mortality rate is 5.5%, slightly above general hospital benchmarks. 
Sepsis, though infrequent, drives the longest stays at 10.12 days. The adjusted 
30-day readmission rate is 21.1%, exceeding the US national benchmark of 15%.

 

## Notebooks
`1_data_exploration.ipynb`: data cleaning, EDA, and visualizations on patient admissions and outcomes
`02_sql_analysis.ipynb`: SQL queries covering admission volume, mortality rates, top diagnoses, and 30-day readmissions.
`clinical_operations_dashboard.pbix`: Interactive Power BI dashboard visualizing key clinical metrics and operational insights

## Recommendations
1. Prioritize urgent admission pathways: highest mortality (13.16%) and longest stays (9.9 days) indicate complex cases requiring enhanced clinical resources
2. Investigate discharge planning processes: 21.1% 30-day readmission rate exceeds the 15% US benchmark, suggesting potential gaps in post-discharge follow-up
3. Monitor high-acuity diagnoses: sepsis and encephalopathy consume disproportionate bed days despite lower admission volume, warranting targeted intervention protocols

## Author
Annabella Baiden-Mensah

Health Data Analyst | BSc Biological Sciences, KNUST
[LinkedIn](https://www.linkedin.com/in/annabellabaidenmensah/)  
