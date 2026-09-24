# Vaccination Data Analysis and Visualization

## Project Overview

This project analyzes global vaccination data to understand vaccination coverage trends, disease incidence, reported cases, vaccine introduction, and vaccine schedule patterns.

The project combines **Python, Exploratory Data Analysis (EDA), SQL, SQLite, and Power BI** to create a complete data analysis workflow for the Public Health and Epidemiology domain.

## Objectives

- Analyze global vaccination coverage trends.
- Study disease incidence and reported cases.
- Identify regional differences in vaccination coverage.
- Analyze vaccine introduction trends.
- Examine vaccine schedule patterns.
- Explore the relationship between vaccination coverage and disease incidence.
- Store cleaned datasets in a structured SQL database.
- Build interactive Power BI dashboards.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- SQL
- SQLite
- Power BI

## Project Workflow

```text
Raw Data
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
CSV Datasets
   ↓
SQLite Database
   ↓
SQL Analysis & Validation
   ↓
Power BI Visualization
   ↓
Insights & Reporting
Datasets

The project uses five major datasets:

Vaccination Coverage
Disease Incidence Rate
Reported Cases
Vaccine Introduction
Vaccine Schedule

Cleaned datasets are provided as CSV files in this repository.

Project Files
File	Description
Vaccination_EDA_Submission_Final.ipynb	Final EDA submission notebook
Data_cleaning.ipynb	Data cleaning and preprocessing
2_SQL_Queries.ipynb	SQL queries and database analysis
vaccination.db	SQLite database
VaccinationFile.pbix	Power BI dashboard
coverage_countries.csv	Country-level vaccination coverage
coverage_groups.csv	Group-level vaccination coverage
incidence_countries.csv	Country-level disease incidence
incidence_groups.csv	Group-level disease incidence
cases_countries.csv	Country-level reported cases
cases_groups.csv	Group-level reported cases
vaccine_introduction.csv	Vaccine introduction data
vaccine_schedule.csv	Vaccine schedule data
Key Analysis

The analysis covers:

Global vaccination coverage trends over time
Country-level vaccination coverage
WHO regional vaccination schedule patterns
Global vaccination coverage map
Disease incidence trends
Vaccination coverage vs. disease incidence
Vaccine introduction trends by WHO region
KPI-based vaccination and disease indicators
Power BI Dashboard

The Power BI report contains interactive visualizations including:

Vaccination Coverage Trend
Country-level Coverage Analysis
WHO Region Schedule Analysis
Global Coverage Map
Disease Incidence Trend
Vaccination Coverage vs Disease Incidence
Vaccine Introduction Trends
KPI Dashboard
Key Findings

The EDA identified a long-term increase in global WUENIC vaccination coverage, with a decline during the pandemic period followed by partial recovery.

Regional differences in vaccination coverage were also observed. The analysis further examined the relationship between MCV1 vaccination coverage and measles incidence using descriptive statistical analysis.

The incidence datasets use different denominators across diseases, so comparisons between different diseases should be interpreted carefully.

Database

The cleaned data is stored in:

vaccination.db

The SQLite database contains tables for vaccination coverage, disease incidence, reported cases, vaccine introduction, and vaccine schedule data.

Conclusion

This project provides a complete workflow for vaccination data analysis, from data cleaning and exploratory analysis to SQL-based validation and Power BI visualization. The results can support monitoring of vaccination coverage, regional disparities, disease indicators, and vaccination program trends.

Author

Arunav Kumar

Project Type: EDA / Data Analysis

Domain: Public Health and Epidemiology

