# Supermarket Sales Practice

An exploratory analysis and modeling practice project on a supermarket sales dataset: 1,000 transactions across three branches, with product line, unit price, quantity, payment type and customer rating.

## Repository Contents

| File | Description |
|---|---|
| `sales figures demo.ipynb` | Full analysis: EDA, linear regression and classification |
| `super market dataset.csv` | Sales dataset (1,000 transactions) |

## Commit History

### `4ad3f18`: Upload of the sales notebook and dataset (2023-03-27)
- **EDA:**
  - total sales per transaction are similar across branches and cities
  - health and beauty products have the highest median total sale
  - most customers buy either 1 or 10 items, and most purchases are $0–$100
- **Simple linear regression:**
  - quantity vs. total sale: R² = 50.8%
  - quantity vs. unit price: almost no relationship (under 1%)
- **Multiple linear regression:**
  - predicted quantity purchased (82.4% fit)
  - predicted unit price (79.0% fit)
- **Classification:** predicted whether a card payment was used with 64% accuracy, which isn't a strong result.

## Tools
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Jupyter Notebook
