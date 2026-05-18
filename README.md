# DSA210 Data Science Project

## Alcohol Consumption and Development Indicators

### Project Description
This project investigates the relationship between alcohol consumption and development indicators across countries between 2010 and 2020.

The analysis combines datasets from the WHO, World Bank, and UNDP to examine how alcohol consumption relates to:
- GDP per capita
- Life expectancy
- Human Development Index (HDI)

The project includes data cleaning, exploratory data analysis (EDA), visualization, hypothesis testing, and machine learning applications.

---

## Research Questions
- Is alcohol consumption related to GDP per capita?
- Is alcohol consumption related to life expectancy?
- Can development indicators help predict alcohol consumption patterns?

---

## Data Sources
- WHO — Alcohol consumption per capita
- World Bank — GDP per capita
- World Bank — Life expectancy
- UNDP — Human Development Index (HDI)

---

## Data Preparation
The datasets were cleaned and merged using country and year information.

The preparation process included:
- filtering country-level observations
- removing missing values
- standardizing country names
- converting datasets from wide format to long format
- merging datasets into a single panel dataset

---

## Exploratory Data Analysis (EDA)
EDA was conducted to better understand:
- variable distributions
- correlations between variables
- country-level differences
- trends over time

Visualizations were created using matplotlib and seaborn.

---

## Hypothesis Testing
Pearson correlation tests were applied to examine statistical relationships between:
- alcohol consumption and GDP per capita
- alcohol consumption and life expectancy

P-values and correlation coefficients were interpreted to determine statistical significance.

---

## Machine Learning
Machine learning models were applied to analyze and predict alcohol consumption patterns using development indicators.

The notebook includes:
- feature selection
- train-test split
- model training
- model evaluation
- interpretation of model performance

---

## Main Findings
- Alcohol consumption showed a statistically significant positive relationship with GDP per capita.
- Alcohol consumption also showed a statistically significant relationship with life expectancy.
- Development indicators provided meaningful information for predicting alcohol consumption patterns.
- The analysis suggests that alcohol consumption patterns differ across countries with different socioeconomic conditions.

---

## Time Period
2010–2020

---

## Files
- `analysis.ipynb` — main Jupyter notebook containing the full analysis
- `analysis.py` — Python script version of the analysis
- `panel_dataset.csv` — cleaned merged dataset
- `panel_dataset_with_latest_hdi.csv` — dataset including HDI values
- `projectproposal-dsa210-idilgulergun.pdf` — project proposal
- `requirements.txt` — required Python libraries

---

## Technologies Used
- Python
- pandas
- matplotlib
- seaborn
- scipy
- scikit-learn

---

## Limitations
- Alcohol consumption data is based on reported estimates
- HDI values were only available as latest observations
- Correlation does not necessarily imply causation
- Some countries had incomplete yearly observations

---

## How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
jupyter notebook analysis.ipynb
```
