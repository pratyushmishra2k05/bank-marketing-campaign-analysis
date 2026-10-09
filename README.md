# Bank Marketing Campaign Analysis

## Project Overview

This project explores a bank marketing campaign dataset to understand customer subscription patterns and identify factors associated with term deposit subscriptions.

## Objectives

- Explore customer demographics and campaign characteristics.
- Measure term deposit subscription rates.
- Compare subscription rates across job categories, age groups, contact methods, campaign months, and previous campaign outcomes.
- Visualize patterns and summarize business insights.

## Dataset

The project uses the **Bank Marketing** dataset from the UCI Machine Learning Repository.

- **Official source:** https://archive.ics.uci.edu/dataset/222/bank+marketing
- **Dataset file:** `bank-additional-full.csv`
- **Target variable:** `y` (`yes` or `no`)

The CSV uses a semicolon (`;`) as its delimiter.

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Structure

```text
Bank Marketing Campaign Analysis/
├── data/
│   └── raw/
├── notebooks/
│   └── Bank_Marketing_EDA.ipynb
├── outputs/
│   └── figures/
├── report/
│   └── Bank_Marketing_EDA_Report.pdf
├── presentation/
│   └── Bank_Marketing_Analysis.pptx
├── .gitignore
└── README.md
```

## Analysis Performed

- Dataset overview and descriptive statistics
- Data types, missing values, unknown categories, and duplicate checks
- Subscription distribution
- Subscription rates by job and age group
- Subscription rates by contact method and previous campaign outcome
- Subscription rates by campaign contact frequency and month
- Correlation analysis of numerical variables

## Key Findings

The notebook calculates subscription rates and presents findings using tables and charts. Specific numerical findings should be added after reviewing the actual notebook results.

## Important Analytical Note

The `duration` variable records the length of the last call. It can be useful for descriptive analysis, but it should not be used as a predictor in a model intended to identify likely subscribers before a call.

## How to Run

1. Install Python and Jupyter Notebook.
2. Install the required packages:

   ```bash
   python -m pip install pandas numpy matplotlib seaborn jupyter ipykernel
   ```

3. Download and extract the dataset from the official UCI source.
4. Place `bank-additional-full.csv` in `data/raw/`.
5. Open `notebooks/Bank_Marketing_EDA.ipynb` in Jupyter Notebook.
6. Run the notebook cells in order.

## Conclusion

This project uses exploratory data analysis to investigate customer subscription patterns and campaign characteristics. The results can help generate hypotheses for improving future campaigns, but the observed associations do not establish causation.