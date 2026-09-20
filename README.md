# Data Professional Survey Breakdown - Power BI Dashboard

## Overview
An interactive Power BI dashboard analyzing survey responses from 630+ data professionals, exploring salary trends, job satisfaction, and demographics across roles, countries, and education levels. Built to practice the full BI workflow from raw data to a polished, stakeholder-ready dashboard.

## Why I built this
I wanted hands-on experience with the complete Power BI pipeline: cleaning messy survey data, building a proper data model, writing DAX measures, and designing visuals that actually answer a business question rather than just displaying numbers.

## What the dashboard shows
- **Country of Survey Takers** - treemap of respondents by country (US, India, UK, Canada, Other)
- **Average Salary by Job Title** - bar chart comparing pay across roles (Data Scientist, Data Engineer, Data Architect, Data Analyst, Database Developer, and others)
- **KPI cards** - total respondent count (630) and average age (29.87)
- **Happiness With Work/Life Balance & Happiness With Salary** - gauge charts scoring satisfaction on a 0–10 scale
- **Favorite Programming Language** - stacked bar chart by job title (Python, R, C/C++, JavaScript, Java, Other)
- **Difficulty to Break Into Data** - donut chart showing how respondents rated entry difficulty into the field

## Process
1. **Data Cleaning (Power Query)** - Fixed data types, removed duplicates and nulls, split/unpivoted multi-select survey columns, and standardized inconsistent free-text entries.
2. **Data Modeling** - Structured the cleaned data into a model suited for analysis, with relationships supporting cross-filtering across visuals.
3. **DAX Measures** — Wrote measures for average salary, average age, and satisfaction scores that recalculate dynamically based on active filters (job title, country, gender).
4. **Visualization & UX** - Chose visual types deliberately (map for geography, bar charts for category comparison, gauges for satisfaction scores against a scale, donut for category share), applied consistent formatting and a cohesive color theme, and added cross-filtering so clicking any visual updates the rest of the report.

## Tools
Power BI Desktop · Power Query · DAX

## Screenshots
<img width="1022" height="574" alt="Data Professional Survey" src="https://github.com/user-attachments/assets/02932bd4-793b-46bf-b88c-c7183c1d0019" />
