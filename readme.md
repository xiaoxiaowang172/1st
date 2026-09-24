# Python & SQL Data Analysis
**Leo Wang | Analytics coursework and practice**

A collection of Jupyter notebooks covering SQL queries, data preparation, exploratory analysis, statistical testing, and introductory modeling. These notebooks document my coursework and practice in using data to answer questions and explain results.

My interests include marketing analytics, customer behavior, experimentation, and business operations.

## Start here

| Notebook | Focus | What to look for |
| --- | --- | --- |
| [SQL & rental data analysis](exercise02.ipynb) | SQLite, pandas, data exploration | Joining film, inventory, rental, and payment tables; filtering customers; building grouped summaries and pivot tables. |
| [Customer segment analysis](lab12.ipynb) | Customer profiles and spending | Comparing eight existing customer segments, summarizing purchasing behavior, and visualizing revenue contribution. |
| [Statistical testing](lab4.ipynb) | Group comparisons and hypothesis tests | ANOVA, two-sample t-tests, Tukey comparisons, and chi-square tests with supporting charts. |
| [Data preparation workflow](01_data_preparation.ipynb) | Cleaning, aggregation, and feature engineering | Standardizing categories, converting numeric fields, aggregating separate datasets, and joining demographic group summaries. |

## Skills demonstrated

- **SQL:** Multi-table joins, filtering, grouping, counts, and averages using SQLite.
- **Python and pandas:** Data loading, cleaning, transformations, merges, aggregation, and pivot tables.
- **Visualization:** Distributions, comparisons, relationships, and time-series plots with Matplotlib and Seaborn.
- **Statistics:** Hypothesis testing, confidence intervals, regression, and diagnostic checks.
- **Introductory machine learning:** Exercises using scikit-learn and XGBoost, including cross-validation and model comparisons.

## More notebooks

| Topic | Files |
| --- | --- |
| Python fundamentals and customer/order summaries | [exercise01](exercise01.ipynb) |
| SQL summaries and visualization | [lab3](lab3.ipynb) |
| Hypothesis testing and regression | [exercise03](exercise03.ipynb), [lab5](lab5.ipynb) |
| Regression, missing values, and diagnostics | [exercise04](exercise04.ipynb), [lab6](lab6.ipynb) |
| Regularization and count models | [exercise05](exercise05.ipynb) |
| Interaction effects | [lab7](lab7.ipynb) |
| Gradient descent and feature scaling | [lab8](lab8.ipynb) |
| Time-series transformations | [lab9](lab9.ipynb) |
| Naive Bayes | [lab10](lab10.ipynb) |
| Weighted summaries and decision trees | [lab11](lab11.ipynb) |
| Logistic regression and tree-based modeling exercises | [exercise06](exercise06.ipynb) |

Original exercise and lab filenames are retained so the coursework remains easy to trace.

## Reading and running the notebooks

Open a notebook on GitHub to review its code, explanations, and saved outputs. To run it locally, use Python with Jupyter Notebook or JupyterLab and install the packages imported by that notebook. Packages used across the collection include pandas, NumPy, Matplotlib, Seaborn, SciPy, statsmodels, scikit-learn, XGBoost, and openpyxl; SQLite is available through Python's standard library.

**Data availability:** The CSV, Excel, and populated database files referenced by many notebooks are not included in this repository. The checked-in `sqlite-sakila.db` is currently empty. Running those notebooks requires the matching source datasets and updated local file paths. The data preparation notebook expects three CSV files under `../data/`; its filenames are defined in the first cell.

## Context and interpretation

These are learning exercises rather than production systems. Saved outputs reflect earlier runs and have not been independently reproduced as part of this repository documentation update.

- The customer segment notebook analyzes **existing segment labels**. Its lift calculation compares segment revenue against an equal-revenue-per-segment baseline; it does not measure causal campaign uplift.
- The data preparation notebook joins **group-level summaries**, not matched individuals. Its engineered scores are practice features, not validated clinical measures.
- Statistical associations and model fit in these exercises should be interpreted within the datasets and assignment assumptions, rather than as causal findings or evidence of production performance.

## About me

I am completing a master's degree in Engineering Management at Washington University in St. Louis, following a bachelor's degree in Managerial Economics from UC Davis. My experience includes digital advertising analysis, KPI reporting, and business operations analytics.

[GitHub profile](https://github.com/xiaoxiaowang172)
