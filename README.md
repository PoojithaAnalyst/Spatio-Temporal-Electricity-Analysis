# Spatio-Temporal-Electricity-Analysis

## Project Overview
This project focuses on analyzing the spatio-temporal patterns of electricity generation in India. It examines historical power generation data to understand temporal trends, seasonal variations, differences in state-level generation patterns, and the relationship between energy sources and carbon emissions.

The project applies statistical analysis, machine learning, time-series modeling, and clustering techniques to explore India's electricity generation patterns and support data-driven insights into the energy sector.

## Objectives
- Analyze temporal trends and seasonal patterns in electricity generation.
- Study differences in power generation across Indian states.
- Examine clean energy generation patterns and state-level variations.
- Investigate relationships between energy sources and carbon emissions.
- Identify important factors associated with carbon intensity.
- Forecast future electricity generation patterns using time-series analysis.

## Dataset
The project uses the "Indian Electricity Consumption dataset", obtained from Kaggle.

Dataset link: https://www.kaggle.com/datasets/rhtsingh/india-monthly-electricity-consumption-20192025

The report describes a dataset containing '223,105 records and 13 original variables' related to electricity generation and energy data.

## Technologies Used
- Programming Language: Python
- Data Analysis: Pandas, NumPy
- Statistical Analysis: SciPy, Statsmodels
- Machine Learning: Scikit-learn
- Data Visualization: Matplotlib
- Time-Series Forecasting: SARIMAX
- Clustering: Hierarchical Agglomerative Clustering

## Methodology
1. Exploratory Data Analysis (EDA): Examined the dataset to understand its structure, distributions, and generation patterns.
2. Feature Engineering: Derived time-related features, including year, month, and energy type.
3. Trend Analysis: Applied the Mann–Kendall test and Sen’s slope estimator to investigate trends over time.
4. Feature Importance Analysis: Used a Random Forest model to examine factors associated with carbon intensity.
5. Time-Series Analysis: Applied Vector Autoregression (VAR) to study relationships among coal generation, solar generation, and total emissions in Gujarat.
6. State-Level Clustering: Used hierarchical agglomerative clustering to group states based on clean energy profiles.
7. Forecasting: Applied a seasonal SARIMAX model to forecast monthly electricity generation.

## Key Areas of Analysis
- Electricity generation trends and seasonality.
- State-wise electricity generation patterns.
- Clean energy adoption and regional differences.
- Relationships between energy sources and carbon emissions.
- Time-series forecasting of electricity generation.

## Project Outcome
The analysis explores temporal trends, seasonal variations, differences in state-level power generation, clean energy profiles, and relationships between energy generation and emissions. The forecasting component demonstrates the application of seasonal time-series modeling to electricity generation data.

## Future Scope
- Incorporate more recent electricity generation data.
- Compare additional forecasting models.
- Improve state-level renewable energy analysis.
- Extend the analysis to support renewable energy planning and emissions monitoring.

## Project Type
Academic Capstone Project — M.Sc. Data Science 
University: Osmania University, Hyderabad

## Note
This repository currently contains the project report in PDF format. The report references a cleaned dataset and Python analysis code.
