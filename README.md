# Amazon-Sales-data-analysis

# Amazon Sales Data Analysis

## Overview
This project analyzes a real-world Amazon sales dataset to understand how pricing, discounts, and product categories influence customer engagement and popularity.

## Business Questions
- How do discounts impact product popularity?
- Do higher discounts always lead to higher engagement?
- How does popularity vary across price segments and categories?
- Which categories offer the highest average discounts?

## Dataset
Source: Amazon Sales Dataset (Kaggle)  
Rows: ~1,400 products  
Key fields: price, discount, rating, rating count, category

## Key Steps
- Data cleaning and data type correction
- Feature engineering (savings, price segments, discount buckets)
- Exploratory data analysis with visual insights
- Popularity analysis using log-transformed rating counts

## Key Insights
- Higher discounts do not always guarantee higher popularity.
- Budget and mid-range products often achieve strong engagement.
- Category and price positioning play a larger role than discount alone.

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Next Steps
With real sales volume or time-series data, this analysis could be extended to revenue forecasting, seasonality detection, and demand modeling.
