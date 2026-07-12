# Data Analytics - Task 1: EDA on Retail Sales + Task 3: Data Cleaning

## Overview
Exploratory Data Analysis on Superstore Sales Dataset (2014-2017) with professional data cleaning.

## Dataset
- Source: Superstore Dataset (Kaggle)
- Size: 9,994 rows × 29 columns
- Period: 2014-2017

## Tech Stack
- Python, pandas, matplotlib, seaborn, Jupyter Notebook

## Tasks Completed

### Task 1: EDA Checklist
- [x] Load dataset and perform initial inspection (shape, dtypes, nulls)
- [x] Descriptive statistics (mean, median, mode, standard deviation)
- [x] Time series analysis (monthly & quarterly sales trends with line charts)
- [x] Customer demographics (segment distribution, region breakdown)
- [x] Product analysis (top 10 best-selling products, revenue by category)
- [x] Correlation heatmap between numerical variables
- [x] Bonus visualization: Profit margin by sub-category (non-obvious insight)
- [x] Markdown observations after each chart
- [x] Conclusion with 3 actionable business recommendations

### Task 3: Data Cleaning Checklist
- [x] Data quality report (nulls, duplicates, dtype issues, anomalies)
- [x] Missing data handling with justified strategy per column
- [x] Duplicate removal with count documented
- [x] Text standardization (Ship Mode, Segment, Category, Region)
- [x] Date format conversion to datetime
- [x] Outlier investigation (retained valid negative profits as business losses)
- [x] Data type correction
- [x] Before vs after summary table
- [x] Saved cleaned dataset to CSV

## Key Insights
1. Tables and Bookcases are loss-making sub-categories despite high sales volume
2. Consumer segment dominates (51.9%) but Corporate segment has higher per-order value
3. Strong seasonal patterns: Q4 consistently outperforms other quarters
4. Discount has negative correlation with Profit (-0.22) — heavy discounts hurt margins

## 3 Actionable Business Recommendations
1. **Address Loss-Making Products:** Review pricing strategy for Tables and Bookcases. Consider supplier renegotiation or product line discontinuation.
2. **Target Corporate Segment:** Develop B2B campaigns with volume discounts and dedicated account management to grow this high-value segment.
3. **Optimize Regional Inventory:** Use quarterly trends to pre-position inventory in high-performing regions (West, East) before peak seasons.

## Note
This notebook also contains Task 2 (Customer Segmentation) and Task 4 (Sentiment Analysis). The complete analysis pipeline is available in this single notebook.
