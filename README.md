# IU-BedCleans
This repository contains my submission for a two-part analytics interview assessment for IU Health North. The objective of the exercise was to demonstrate data analysis thinking, Excel proficiency, and the ability to communicate insights clearly to non-technical stakeholders in a healthcare setting.

IUHealth_BedCleaning_Analytics/
├── README.md
├── Part_One_BedCleaning_Analysis.pdf      # 1-page summary with findings and recommendations
├── Part_One_Cleaning_Time_Analysis.xlsx   # Supporting Excel/Power BI workbook
├── Part_Two_Excel_Employee_Summary.xlsx   # Deliverable tab with formulas and explanation
✅ Part One – Cleaning Time Analysis (Med Surg Units)


Goal: Evaluate how long it takes to clean hospital beds on units 5B Medical and C5 Surgical using timestamp data.

Approach:
Cleaned and transformed raw data
Calculated key metrics: time to start cleaning, cleaning duration, and total turnaround time
Created summary tables and visuals to reveal bottlenecks

Findings:
Average delay from “bed dirty” to “clean start” exceeded 40 minutes on both units
Cleaning time itself was consistent; delays stemmed from task initiation
Identified opportunity for staff scheduling or alert-based improvements

✅ Part Two – Excel-Based Data Integration & Summary

Goal: Use Excel to combine and summarize timestamp and staffing data from multiple sheets.

Tasks Completed:
Count of unique room/campus/unit combinations cleaned by each employee
Average number of rooms cleaned by each employee per campus (sorted by last name)
Count of room cleanings started by hour per campus

Techniques Used:
COUNTIFS, AVERAGEIFS, TEXT TO COLUMNS, HOUR, Pivot Tables

Used a single presentation tab with helper formulas and a text box explaining methodology

📊 Tools Used
Microsoft Excel (primary)
Power BI (optional for visuals in Part One)
Data wrangling with basic formulas and pivot tables
