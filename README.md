# DecodeLabs Project 1 — Sales Analysis

## Project Summary

This project analyzes property sales data to uncover pricing patterns, market composition, and temporal trends. The analysis covers data cleaning, exploratory analysis, and summary statistics to inform pricing strategy and inventory decisions.

## Data

- `raw_sales.csv`: Original dataset as provided.
- `cleaned_sales.csv`: Post-processed dataset used for analysis (duplicates and invalid records removed).

## Key Steps

1. Data ingestion and validation
2. Data cleaning: de-duplication, price validation, and normalization
3. Exploratory analysis: distributions, aggregates by year and property attributes
4. Correlation analysis between price and features (e.g., bedroom count)

## Key Findings

- Houses have higher average prices than units.
- Prices have generally trended upward over the years with some fluctuations.
- 3 and 4 bedroom properties are the most common segments.
- There is a clear positive correlation between number of bedrooms and price.

## How to run

Prerequisites: Python 3.8+ with `pandas`, `numpy`, and `matplotlib`/`seaborn` for plotting.

1. Create a virtual environment (optional):

```bash
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
```

2. Open and run the notebook `task1.ipynb` to reproduce the analysis and visualizations.

## Next steps

- Enrich the dataset with geographic and property-condition features.
- Train a predictive pricing model to forecast price changes and identify price drivers.

## Contact

For questions or further work, contact the project author.
