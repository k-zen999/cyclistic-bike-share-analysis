# Cyclistic Bike-Share Data Analysis

**Google Data Analytics Professional Certificate Capstone Project**

## Overview
Data analysis of Cyclistic (Divvy) bike-share trip data to understand how annual members and casual riders use the bikes differently. The goal is to provide actionable insights to help convert casual riders into annual members and increase long-term profitability.

## Business Task
The objective of this analysis is to identify behavioral differences between casual riders and annual members. These insights will support the marketing team in developing targeted strategies to convert casual riders into loyal members.

## Tools Used
- **Python**: pandas, numpy (data cleaning, processing, and analysis)
- **Tableau**: Data visualization and dashboard creation
- **Jupyter Notebook**: Reproducible workflow

## Dataset
This analysis uses 12 months of Cyclistic bike-share trip data (June 2025 – May 2026). The dataset consists of monthly CSV files containing trip-level details such as start/end times, stations, rideable type, and user type (member or casual).

## Project Steps
- Downloaded and extracted 12 months of raw CSV files.
- Concatenated all files into a single dataframe.
- Performed comprehensive data cleaning and preprocessing (handled missing values, removed duplicates, validated ride durations, created calculated fields).
- Created a representative sample of **500,000 records** for efficient analysis.
- Conducted exploratory data analysis and built visualizations in Tableau.

## Key Insights
- **Member riders dominate usage** (63.38% of total rides) compared to casual riders (36.62%).
- **Casual riders take significantly longer trips** on average (~23 minutes) than members (~13 minutes), indicating more leisure-oriented usage.
- **Weekly patterns differ clearly**: Members prefer weekdays (peak Tuesday–Thursday), while casual riders favor weekends (especially Saturday).
- **Hourly patterns** show member rides concentrated during commuting hours, while casual rides are more evenly distributed.
- **Strong seasonal trend**: Ride volume peaks in summer months (June–August) and drops in winter.
- **Rideable type preference**: Members heavily prefer electric bikes, while casual riders use both types more evenly.

## Visualizations
Here are key charts from the analysis:

![Weekly Ride Distribution by User Type](Visualizations/weekly_ride_distribution.png)

![Hourly Ride Patterns](Visualizations/hourly_patterns.png)

![Monthly Ride Volume](Visualizations/monthly_volume.png)

![Proportion of Members vs Casual](Visualizations/member_casual_pie.png)

![Average Ride Duration](Visualizations/avg_ride_duration.png)

![Rideable Type](Visualizations/rideable_type.png)
## Repository Structure
