# Patient Data Analysis Project

## Overview
This project is an exploratory data analysis (EDA) of a hospital patient dataset using **Python (pandas, seaborn, matplotlib).**  
The goal is to practice data cleaning, visualization, and summarizing insights in a clear, structured way.

## Tools & Libraries
- **pandas** -> data loading and cleaning  
- **numpy** -> basic calculations  
- **matplotlib / seaborn** -> visualizations  
- **datetime** -> working with dates  

## Dataset
The dataset contains 1,000 patient records with the following columns:
- `patient_id`  
- `name`  
- `age`  
- `arrival_date`  
- `departure_date`  
- `service` (ICU, surgery, emergency, general medicine)  
- `satisfaction` (0–100 scale)

##  Analysis Steps
1. **Data Inspection** -> checked column types and summary statistics.  
2. **Data Cleaning** -> converted dates and calculated `length_of_stay`.  
3. **Exploratory Analysis** -> distributions of age, satisfaction, and stay length.  
4. **Comparisons** -> average satisfaction and stay length by service.  
5. **Visualizations** -> histograms, boxplots, scatterplots, and correlation heatmap.  

## Key Findings
- ICU patients had the **longest stays** but reported **lower satisfaction**.  
- Surgery patients had **shorter stays** but **higher satisfaction**.  
- Age had little effect on satisfaction, but older patients tended to stay longer.  
