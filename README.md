# Retail Sales EDA

## Objective
Perform a thorough Exploratory Data Analysis on a retail sales dataset to uncover patterns, customer behaviour trends and actionable business insights.

## Dataset
Retail sales data with 1,000 transactions and 9 columns (date, customer ID, gender, age, product category, quantity, price per unit, total amount). There are no missing values.

## Tools
Python, pandas, matplotlib, seaborn, Jupyter Notebook

## What I did
- [x] Loaded the data and checked shape, data types and null values
- [x] Calculated mean, median, mode and standard deviation
- [x] Plotted monthly and quarterly sales trends (line charts)
- [x] Analysed customers by age group and gender
- [x] Compared product categories by quantity sold and revenue (bar charts)
- [x] Built a correlation heatmap of the numerical variables
- [x] Added an extra chart: average spending by age group
- [x] Wrote observations in markdown after each chart
- [x] Wrote a conclusion with business recommendations

## Key findings
- Clothing sold the most units (894), and Electronics earned the most revenue.
- Sales were highest in Quarter 4 (126,190) and lowest in Quarter 3. May was the best month and September the weakest.
- Customers aged 18 to 27 had the highest average transaction (504.28), even though the 48 to 57 group is the largest.
- Price per unit and total amount are strongly correlated (0.85).
- The customer base is fairly balanced by gender.

## Business recommendations
- Prioritise Clothing stock and promotions.
- Target customers aged 18 to 37 with bundles and campaigns.
- Evaluate premium products, since higher prices drive transaction value.
- Plan stock and marketing around Quarter 4 and May, and run offers in September.

## Notes
- The dataset has no product names, so a top 10 products analysis was not possible. Product Category was used instead.
- Two transactions dated in 2024 were excluded from the monthly and quarterly trends, so those cover 2023 only.

## Files
- `Retail_Sales_EDA.ipynb`: the notebook
- `retail_sales_dataset.csv`: the data
