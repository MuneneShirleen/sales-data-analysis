
# Sales Data Analysis with Python

## Project Overview

This project analyzes a simulated retail sales dataset using Python, pandas, and Matplotlib. It explores product performance, category revenue, monthly sales trends, and profitability to generate actionable business insights.

## Project Objectives

- Calculate revenue, total costs, and profit.
- Identify top-performing products by revenue and units sold.
- Compare sales and profitability across product categories.
- Analyze monthly revenue and profit trends.
- Create visualizations to communicate business findings.
- Export summary reports for further analysis.

## Tools and Technologies

- Python
- pandas
- Matplotlib
- Google Colab
- GitHub

## Dataset

The dataset contains 20 simulated sales records covering January to March 2026.

Each record includes:
- Date
- Product
- Product category
- Quantity sold
- Unit selling price
- Unit cost
- Total revenue
- Total cost
- Profit

**Note:** The dataset is fictional and was created for educational and portfolio purposes. It does not represent actual business transactions.

## Key Performance Indicators

| Metric | Result |
|---|---:|
| Total Revenue | KSh 1,441,900 |
| Total Profit | KSh 311,500 |
| Overall Profit Margin | 21.60% |
| Number of Sales Records | 20 |
| Number of Product Categories | 3 |
| Number of Unique Products | 6 |

## Key Findings

### 1. Product Performance

- Laptops generated the highest revenue at KSh 650,000.
- Laptops also generated the highest total profit at KSh 130,000.
- Mice recorded the highest sales volume, with 37 units sold.
- Phones generated KSh 490,000 in revenue.

### 2. Category Performance

Electronics was the leading category, generating KSh 1,140,000 in revenue and KSh 214,000 in profit.

Furniture generated KSh 210,000 in revenue, while accessories generated KSh 91,900.

Electronics accounted for approximately 79.1% of total revenue.

### 3. Monthly Performance

| Month | Revenue | Profit |
|---|---:|---:|
| January 2026 | KSh 329,500 | KSh 74,000 |
| February 2026 | KSh 416,500 | KSh 91,000 |
| March 2026 | KSh 695,900 | KSh 146,500 |

March recorded the highest revenue and profit. Revenue increased by approximately 67.1% from February to March.

## Visualizations

### Revenue by Product

![Revenue by Product](images/revenue_by_product.png)

### Monthly Revenue Trend

![Monthly Revenue Trend](images/monthly_revenue_trend.png)

### Profit by Category

![Profit by Category](images/profit_by_category.png)

## Business Recommendations

Based on the simulated dataset:

1. **Monitor electronics performance:** Electronics contributes the largest share of revenue. Monitor demand, costs, and margins in this category.
2. **Review laptop profitability:** Laptops lead both revenue and profit. Investigate whether this performance remains consistent over a longer period.
3. **Track monthly trends:** Investigate the factors behind March's higher revenue before assuming the increase will continue.
4. **Evaluate product margins:** Compare profit margins across products to support pricing and purchasing decisions.
5. **Expand the analysis:** Use a larger dataset covering more months to test whether these patterns persist.

These recommendations are preliminary because the dataset is small and simulated.

## Project Structure

```text
sales-data-analysis/
├── data/
│   └── sales_data.csv
├── reports/
│   ├── product_summary.csv
│   ├── category_summary.csv
│   └── monthly_summary.csv
├── images/
│   ├── revenue_by_product.png
│   ├── monthly_revenue_trend.png
│   └── profit_by_category.png
├── sales_analysis.ipynb
└── README.md
```

## Limitations

- The dataset contains only 20 sales records.
- The data is simulated rather than collected from a real business.
- The analysis covers only three months.
- The results demonstrate analytical methods and should not be treated as evidence of actual market performance.

## Future Improvements

- Analyze a larger, real-world sales dataset.
- Add customer segmentation and sales forecasting.
- Investigate seasonal patterns over a longer period.
- Build an interactive dashboard.
- Add automated data validation checks.

## Author

**Shirleen Munene**

GitHub: [MuneneShirleen](https://github.com/MuneneShirleen)

Project Repository: [Sales Data Analysis](https://github.com/MuneneShirleen/sales-data-analysis)
