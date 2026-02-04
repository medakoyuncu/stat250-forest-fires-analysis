# STAT250 Forest Fires Analysis

This repository contains the final project report for the **STAT250: Applied Statistics** course at Middle East Technical University.

## Project Overview
This project investigates forest fires in Montesinho Park, Portugal, using exploratory data analysis and inferential statistical methods. The main objective is to understand how meteorological and environmental variables are related to fire behavior and burned area.

## Research Questions
- How do environmental and meteorological variables influence the Fine Fuel Moisture Code (FFMC)?
- Is there a significant difference in the average burned area across different months?
- What is the relationship between temperature and burned area?

## Methodology
- Exploratory Data Analysis (EDA) using summary statistics and visualizations  
- Multiple Linear Regression modeling  
- Assumption checking (normality, homoscedasticity, multicollinearity, independence)  
- One-way ANOVA and Kruskal–Wallis Test  
- Two-sample t-test  
- Model diagnostics and interpretation  

## Key Results
- **FFMC Analysis:**  
  Multiple linear regression results showed that **Drought Code (DMC)**, **Initial Spread Index (ISI)**, and **Relative Humidity (RH)** have statistically significant effects on FFMC.  
  The fitted model explained a moderate proportion of variability in FFMC, indicating that these variables play an important role in fire susceptibility.

- **Seasonal Differences in Burned Area:**  
  One-way ANOVA results indicated no significant difference in average burned area across months; however, the normality assumption was violated.  
  Therefore, a **Kruskal–Wallis test** was applied, which revealed a **statistically significant difference** in burned area across different months.

- **Temperature and Burned Area Relationship:**  
  A two-sample t-test comparing August and December showed **no statistically significant difference** in average burned area between these months.  
  This result suggests that temperature alone may not be sufficient to explain variations in burned area.

## Tools
- R  
- Statistical inference techniques  
- Data visualization tools  

## Files
- `STAT250_Forest_Fires_Project_Report.pdf` — Final project report

## Notes
This repository is intended for academic and portfolio purposes.
