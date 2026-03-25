# Dallas Crime Analysis & Prediction

## Overview
This project analyzes Dallas Police Department crime incident data from January 2022 to January 2025, covering 337,796 incidents across 65 variables. The goal is to uncover crime patterns, build a machine learning classifier, and visualize insights through an interactive Tableau dashboard.

## Project Structure
- `dallas_crime_analysis.ipynb` — Main Jupyter notebook with full analysis
- `dallas_crime_heatmap.html` — Interactive crime heatmap
- `dallas_crime_choropleth.html` — Interactive choropleth map by zip code

## Key Findings
- Motor Vehicle Theft and Miscellaneous are the most common crimes in Dallas
- Crime peaks on Fridays and Saturdays and during evening hours
- Central Dallas has the highest crime concentration
- Average police response time is 20 minutes across all divisions
- Northeast division has the slowest response time

## Machine Learning
Built a Random Forest classifier to predict crime category based on time and location features.

| Model | Accuracy |
|-------|----------|
| AdaBoost | 53.84% |
| XGBoost | 58.43% |
| Random Forest | 59.39% |

## Interactive Maps
- [Crime Heatmap](https://anithaMorampudi.github.io/dallas-crime-analysis/dallas_crime_heatmap.html) — Crime density across Dallas
- [Crime Choropleth](https://github.com/AnithaMorampudi/dallas-crime-analysis/blob/main/dallas_crime_choropleth.html) — Crime by zip code

## Tableau Dashboard
Interactive dashboard published on Tableau Public:
[Dallas Crime Analysis Dashboard](https://public.tableau.com/app/profile/anitha.morampudi/viz/DallasCrimeAnalysisDashboard/DallasCrimeAnalysisDashboardshboard1)

## Tools Used
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn, XGBoost, folium)
- Jupyter Notebook
- Tableau Public

## Data Source
Dallas Police Department open crime incident data
