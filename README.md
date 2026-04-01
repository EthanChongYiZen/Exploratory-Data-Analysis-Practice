# Python Exploratory Data Analysis Practice

A practice project for performing Exploratory Data Analysis (EDA) on a shopping trends dataset using Python.

## Overview

This notebook explores customer shopping behaviour using statistical summaries and visualizations. It covers common EDA techniques including distribution analysis, group comparisons, and box plots.

## Tech Stack

- Python 3
- pandas
- matplotlib
- numpy

## Getting Started

**Prerequisites**

```bash
pip install pandas matplotlib numpy
```

**Run the notebook**

1. Clone the repository
2. Place `shopping_trends.csv` in the project root
3. Open `Python_Exploratory_Data_Analysis_Practice.ipynb` in Jupyter and run all cells

## Dataset

The dataset (`shopping_trends.csv`) contains 3,900 customer records with the following columns:

| Column | Description |
|--------|-------------|
| Customer ID | Unique identifier |
| Age | Customer age |
| Gender | Male / Female |
| Item Purchased | Name of item bought |
| Category | Clothing, Footwear, Accessories |
| Purchase Amount (USD) | Transaction value |
| Location | US state |
| Size | Item size (S, M, L) |
| Color | Item color |
| Season | Season of purchase |
| Review Rating | Customer rating |
| Subscription Status | Yes / No |
| Payment Method | Credit Card, PayPal, Cash, etc. |
| Shipping Type | Standard, Express, etc. |
| Discount Applied | Yes / No |
| Promo Code Used | Yes / No |
| Previous Purchases | Number of past purchases |
| Preferred Payment Method | Customer's preferred method |
| Frequency of Purchases | Weekly, Monthly, etc. |

## Analysis Performed

- Data loading and initial inspection
- Summary statistics
- Distribution of purchase amounts
- Review rating analysis by gender (box plot)
- Category and seasonal breakdowns

## Notes

- This is a practice project focused on learning EDA techniques
- Dataset is for educational purposes
