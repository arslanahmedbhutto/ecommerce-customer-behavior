# Dataset

This project uses the **E-commerce Customer Behavior Dataset** from Kaggle:
https://www.kaggle.com/datasets/uom190346a/e-commerce-customer-behavior-dataset

Download the CSV (you need a free Kaggle account) and save it here as **`data/ecommerce_customer_behavior.csv`**.

## Columns

| Column | Description |
|--------|-------------|
| Customer ID | Customer identifier |
| Gender | Male / Female |
| Age | Age in years |
| City | Customer city (6 US cities) |
| Membership Type | Gold / Silver / Bronze |
| Total Spend | Total amount spent ($) |
| Items Purchased | Number of items bought |
| Average Rating | Average product rating given (1–5) |
| Discount Applied | Whether a discount was applied (True / False) |
| Days Since Last Purchase | Days since the customer's most recent purchase |
| Satisfaction Level | Satisfied / Neutral / Unsatisfied (2 missing values) |

The notebook replaces spaces in column names with underscores and defines **Churned** as `Days Since Last Purchase > 30`.
