# GDP Dashboard

A Streamlit data-visualization project that explores country-level GDP trends using a local CSV dataset.

## What the App Shows

- GDP trends over a selected range of years.
- Country selection for comparing multiple economies.
- Interactive line-chart visualization.
- Summary metrics for selected countries in the chosen ending year.

## Data Source & Coverage

The included dataset is based on World Bank GDP data and currently covers 1960–2022. The available years and countries depend on the records in the CSV file; some observations may be missing. This is a historical-data demonstration, not a live GDP feed.


## Known Data Limitation

The dataset contains missing country-year observations. The current summary-metric code assumes a selected country has a value at both selected year boundaries; choosing a country or year with a missing value may cause the summary section to fail. The chart and summary should therefore be treated as a learning demonstration until missing-value handling is added.

## Technology

- Python
- Streamlit
- Pandas

## Run Locally

```bash
git clone https://github.com/zulqarnainjadoon99/gdp-dashboard.git
cd gdp-dashboard
pip install -r requirements.txt
streamlit run streamlit_app.py
```

## Project Purpose

This project demonstrates loading and reshaping tabular data with Pandas, filtering datasets, and presenting time-series information through Streamlit.

## Developer

**Zulqarnain Khan Jadoon**  
GitHub: https://github.com/zulqarnainjadoon99  
Portfolio: https://zulqarnainjadoon99.github.io

---

*This repository is based on a Streamlit dashboard project template and adapted as a learning/portfolio exercise. The app should be run locally using the included source and dataset.*