# Data Professional Survey Breakdown - Power BI Dashboard

## Overview
An interactive Power BI dashboard analyzing survey responses from 630+ data professionals, exploring salary trends, job satisfaction, and demographics across roles, countries, and education levels. Built to practice the full BI workflow — from raw data to a polished, stakeholder-ready dashboard.

## Why I built this
I wanted hands-on experience with the complete Power BI pipeline: cleaning messy survey data, building a proper data model, writing DAX measures, and designing visuals that actually answer a business question rather than just displaying numbers.

## What the dashboard shows
- Average salary by job title and by gender
- Respondent demographics by country, education, and ethnicity
- Job satisfaction: happiness with salary and work-life balance (gauge visuals)
- Favorite programming language among respondents
- KPI cards for total respondents and average age

## Process
1. **Data Cleaning (Power Query)** - Fixed data types, removed duplicates and nulls, split/unpivoted multi-select survey columns, and standardized inconsistent free-text entries.
2. **Data Modeling** - Structured the cleaned data into a model suited for analysis, with relationships supporting cross-filtering across visuals.
3. **DAX Measures** - Wrote measures for average salary, average age, and satisfaction scores that recalculate dynamically based on active filters (job title, country, gender).
4. **Visualization & UX** - Chose visual types deliberately (map for geography, bar charts for category comparison, gauges for satisfaction scores against a scale, donut for category share), applied consistent formatting and a cohesive color theme, and added cross-filtering so clicking any visual updates the rest of the report.

## Tools
Power BI Desktop · Power Query · DAX

## Note
This project is based on a guided tutorial (Alex The Analyst's Power BI course) and adapted with my own [measures/visuals/formatting choices — *fill in what you actually changed*] as part of learning Power BI end to end.

## Files
- `data-professional-survey.pbix` - Power BI project file
- `screenshots/` - dashboard preview images
