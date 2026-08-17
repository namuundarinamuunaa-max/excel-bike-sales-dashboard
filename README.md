# excel-bike-sales-dashboard
# 🚲 Bike Sales Dashboard | Excel

## Project Overview

This project analyzes bike customer data using Microsoft Excel. I cleaned and prepared the dataset, created PivotTables, and built a dashboard to better understand customer purchasing behavior.

The main goal of this project was to practice Excel data cleaning, PivotTables, PivotCharts, and dashboard creation.

## Tools Used

* Microsoft Excel
* PivotTables
* PivotCharts
* IF formulas
* Data cleaning
* Data visualization
* Dashboard creation

## Data Preparation

Before building the dashboard, I cleaned and organized the dataset by:

* Standardizing marital status values
* Standardizing gender values
* Organizing commute distance categories
* Creating age groups
* Preparing the data for PivotTable analysis

Example formula used for age groups:

`=IF(L2>54,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid")))`

## Analysis

The PivotTables were used to analyze:

* Average income by gender
* Bike purchases by age group
* Bike purchases by commute distance
* Differences between customers who purchased a bike and customers who did not

## Dashboard

The final dashboard includes multiple charts that make it easier to compare customer characteristics and bike purchasing behavior.

![Bike Sales Dashboard] <img width="892" height="650" alt="Screenshot 2026-08-17 at 11 44 34 AM" src="https://github.com/user-attachments/assets/13ed7e35-63d9-485e-a83e-507e7fb1604b" />


## Key Insights

* Middle-aged customers represented a large portion of bike buyers.
* Purchasing behavior differed depending on commute distance.
* Income levels varied between customers who purchased bikes and those who did not.
* PivotTables made it easier to summarize and compare customer groups.

## Workbook Structure

* **bike_buyers** – Original dataset
* **Working Sheet** – Cleaned and prepared dataset
* **Pivot Table** – PivotTable analysis
* **Dashboard** – Final dashboard and visualizations

## Skills Demonstrated

This project demonstrates my ability to:

* Clean and organize data in Excel
* Use formulas to create new categories
* Create PivotTables
* Build PivotCharts
* Analyze customer data
* Present findings using an Excel dashboard
