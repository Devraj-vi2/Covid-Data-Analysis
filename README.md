# COVID-19 Global Data Analysis with Python

This project presents an exploratory data analysis (EDA) of COVID-19 global trends using publicly available datasets. The goal is to extract meaningful insights from the pandemic data using visualizations, trend analysis, and correlation metrics.

---

## Objective

To uncover patterns in global COVID-19 transmission, fatalities, and recoveries by:

- Cleaning and preprocessing the dataset
- Identifying top affected countries
- Analyzing global time series trends
- Evaluating fatality and recovery rates
- Performing correlation analysis among confirmed, deaths, and recovered cases

---

## Dataset

Dataset Source: [Johns Hopkins University CSSE COVID-19 Dataset](https://github.com/CSSEGISandData/COVID-19) or [Kaggle - Coronavirus Report](https://www.kaggle.com/datasets/imdevskp/corona-virus-report)

Key Columns Used:
- `ObservationDate`
- `Country/Region`
- `Confirmed`
- `Deaths`
- `Recovered`

---

## Tools & Technologies

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## Key Analyses

- Top 10 countries by confirmed cases
- Global spread over time
- Active case calculation
- Fatality vs. Recovery Rate comparison
- Heatmap of correlation between COVID-19 metrics

---

## Project Highlights

- Built a time series analysis dashboard for global COVID-19 trends.
- Used Seaborn and Matplotlib for rich visualizations.
- Analyzed data from hundreds of countries over time.
- Derived actionable insights on which countries managed recovery more efficiently.

---

## Sample Output Visuals

- Barplot: Top 10 Countries by Confirmed Cases
- Line Chart: Global Confirmed, Deaths, and Recovered over Time
- Scatter Plot: Fatality Rate vs. Recovery Rate by Country
- Heatmap: Correlation Matrix of COVID Metrics

---

## How to Run

```bash
pip install pandas matplotlib seaborn jupyter
jupyter notebook
