# Power BI – Household Consumption & Health Analysis

## Project Overview
This Power BI project analyses household food consumption, expenditure patterns,
BMI and obesity indicators based on publicly available Czech statistical data and data from Eurostat.
The goal of the project was to identify long-term trends and relationships between
consumption structure, physical activity and health outcomes.

## Tools Used
- Power BI
- Power Query (ETL and data transformation)
- DAX (custom measures and KPIs)
- Excel (initial data validation)

## Data Sources
The analysis is based on publicly available Czech statistical data and health statistics from Eurostat.
Raw datasets are not included in the repository due to size and licensing constraints.

## Data Model
The report is built using a star-schema-like structure with a central calendar table
and fact tables for consumption, expenditure and health indicators.

## Key Metrics
- Consumption index (base year = 2014)
- Share of category in total expenditure
- Year-over-year change
- Average BMI and obesity rate

## Report Pages
1. Overview – key trends and summary indicators
2. Food Consumption – structure and development over time
3. Household Expenditure – structure and development over time
4. Health Indicators – BMI and obesity trends, physical activity 


## Dashboard Preview
![Overview](screenshots/1%20-%20overview.png)
![Food Consumption](screenshots/2%20-%20food%20consumption.png)
![Household Spending](screenshots/3%20-%20household%20spending.png)
![Health](screenshots/4%20-%20health.png)


## Repository Content
- `project.pbix` – main Power BI report file
- `/Screenshots` – dashboard previews

## Purpose
This project was created as a portfolio and training project to demonstrate
analytical thinking, Power BI data modeling, DAX usage and data storytelling.
