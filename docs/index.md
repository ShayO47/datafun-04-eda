# Restaurant Tips Exploratory Data Analysis

This project explores restaurant tipping patterns using Seaborn's built-in
`tips` dataset. The analysis uses Python, pandas, Seaborn, and Jupyter
notebooks to examine bill totals, tip amounts, meal times, days of the week,
and party sizes.

## Research Question

How do party size, meal time, and day of the week relate to restaurant tip
amounts?

## Dataset

The dataset contains 244 restaurant bills and 7 columns. Each row represents
one restaurant bill and includes the total bill, tip amount, customer
characteristics, meal time, day of week, and party size.

The data was loaded with Seaborn's built-in `tips` dataset:

```python
sns.load_dataset("tips")
```

## Key Findings

* **Data quality:** The dataset has no missing values.
* **Bills and tips:** Total bill and tip amount have a positive correlation
  of 0.68.
* **Typical tip percentage:** The larger groups generally average about 15%
  to 19%.
* **Party-size limitation:** Some party sizes have few observations, so they
  require careful interpretation.
* **Outliers:** A small number of unusually high tip percentages appear in
  the data.

## Interpretation

Larger restaurant bills generally receive larger tips, although bill total does
not explain every difference in tipping behavior. Tip percentages are broadly
similar across the larger meal-time and day-of-week groups. Small group sizes
and unusual outliers are important limitations when interpreting the results.

## Analysis Notebook

The complete narrated analysis, including tables, charts, observations, and
next steps, is available in the
[Restaurant Tips EDA notebook](https://github.com/ShayO47/datafun-04-eda/blob/main/notebooks/eda_shalynne.ipynb).

## Next Step

A useful follow-up analysis would build a statistical model of tip percentage
using bill total, party size, meal time, day of week, and smoker status.
