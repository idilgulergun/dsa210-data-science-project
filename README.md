# dsa210-data-science-project
DSA210 Introduction to Data Science Term Project
# Alcohol Consumption and Development Indicators

## Project Description
This project analyzes the relationship between alcohol consumption and development indicators using cross-country data.

## Data Sources
- WHO: Alcohol consumption (total per capita, 15+)
- World Bank: GDP per capita
- World Bank: Life expectancy
- UNDP: Human Development Index (HDI)

## Data Preparation
Datasets were cleaned and merged based on country and year.
World Bank data was converted from wide format to long format.
Missing values were removed and country names were standardized.

## Analysis
This milestone includes:
- Data collection
- Data cleaning
- Exploratory Data Analysis (EDA)
- Visualization
- Hypothesis testing using Pearson correlation

## Time Period
2010–2020

## Files
- `analysis.py`: main Python script
- `panel_dataset.csv`: cleaned dataset
- `panel_dataset_with_latest_hdi.csv`: extended dataset
- `projectproposal-dsa210-idilgulergun.pdf`: proposal

## Limitations
- Alcohol data is based on a three-year average
- HDI is only available as a latest value

## How to Run
1. Install dependencies:
   pip install -r requirements.txt

2. Run:
   python analysis.py
