# NYC Household Vehicle Survey — Dashboard

## Overview
Interactive Excel dashboard analyzing household vehicle data from NYC's 
Citywide Mobility Survey (data.cityofnewyork.us, dataset qhkz-4dqm). 
The dataset covers 1,784 vehicle records across NYC households.

## What I Did
- Cleaned and validated the raw data (checked for duplicates on hh_id)
- Built a fuel-type lookup table and mapped numeric codes to readable labels
- Created calculated columns: vehicle age and age group classification
- Built 3 Pivot Tables and matching charts:
  - Vehicle count by fuel type
  - Average vehicle age by fuel type
  - Average citywide statistical weight by fuel type
- Added an interactive Slicer connected to all Pivot Tables
- Applied a consistent color theme across the dashboard

## Key Insights
1. Gasoline vehicles dominate the sample (90.9%, 1,622 of 1,784 records)
2. Hybrid and Electric vehicles are notably newer on average (3.6 and 4.9 
   years) compared to Gasoline and Diesel (10.3 and 7 years)
3. Plug-in Hybrid and "Don't Know" fuel-type categories show extreme 
   average values (highest citywide weight and highest vehicle age, 
   respectively) — but each contains only 2-3 records out of 1,784, so 
   these averages are not statistically reliable

## AI Assistance Disclosure
I used Claude (Anthropic) as a learning guide throughout this project — 
it explained concepts (VLOOKUP, nested IF/IFS, Pivot Table mechanics, 
Slicer connections) and reviewed my work step-by-step, but I built the 
formulas, Pivot Tables, charts, and dashboard myself in Excel.

## Data Source
NYC Open Data — Citywide Mobility Survey, Vehicle table
https://data.cityofnewyork.us/resource/qhkz-4dqm.json
