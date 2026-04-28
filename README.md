# Data-Science
Data Science in SoftUni.

# FMCG Sales Drivers Analysis

## Overview
This project analyzes the key drivers of FMCG beverage sales using a multivariate statistical and econometric approach. It combines sales, store operations, equipment, and weather data to understand what factors influence retail performance.

## Objective
To identify and quantify the impact of:
- Store visits (field execution)
- Weather conditions
- Store execution quality (equipment / coolers)
- Store characteristics (segment, region, channel)

on daily sales performance.

## Data Sources
- Sales – daily revenue and volume per store  
- Visits – field force activity  
- Store data – segment, region, channel  
- Equipment data – in-store execution quality  
- Weather – temperature, humidity, precipitation  

## Methodology
- Data integration from multiple sources  
- Feature engineering (lags, interactions, seasonality)  
- Exploratory data analysis (EDA)  
- Statistical testing (t-tests, ANOVA, correlation)  
- Regression modeling (OLS)  
- Fixed effects panel regression  

## Key Findings
- Equipment availability is the strongest and most consistent driver of sales  
- Weather (especially temperature) has a measurable impact on demand  
- Store visits are positively related to sales but may suffer from endogeneity  
- Strong heterogeneity exists across store types and regions  

## Tools
Python, Pandas, NumPy, Statsmodels, SciPy, Matplotlib, Seaborn

## Notes
Results show strong statistical relationships but limited causal identification due to observational data constraints.
