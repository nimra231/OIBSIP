# Data Analytics - Task 2: Customer Segmentation Analysis

## Overview
Applied RFM (Recency, Frequency, Monetary) analysis and K-Means clustering to segment customers based on purchasing behavior.

## Dataset
- Cleaned Superstore dataset from Task 1
- 9,994 transactions → ~793 unique customers

## Tech Stack
- Python, pandas, scikit-learn, matplotlib, seaborn

## Tasks Completed
- [x] Load dataset and inspect structure; handle missing values
- [x] Descriptive statistics (average purchase value, frequency, customer lifetime value)
- [x] Feature selection: RFM (Recency, Frequency, Monetary)
- [x] Data standardization using StandardScaler
- [x] K-Means clustering with Elbow Method for optimal K
- [x] Cluster visualization using scatter plots (2 feature combinations)
- [x] Cluster profiling with mean feature values per cluster
- [x] Bar chart: number of customers per cluster
- [x] Marketing action recommendations for each segment

## Cluster Profiles

| Cluster | Name | Recency | Frequency | Monetary | Marketing Action |
|---------|------|---------|-----------|----------|------------------|
| 0 | Champions | Low | High | High | VIP programs, early access, referral rewards |
| 1 | At Risk | High | Low | Low | Win-back campaigns, special discounts |
| 2 | Loyal Customers | Low | Medium | Medium | Upsell/cross-sell, loyalty rewards |
| 3 | New Customers | Low | Low | Low | Onboarding series, welcome discounts |

## Note
This analysis builds on the cleaned dataset from Task 1. The full notebook containing all tasks is also available in the Task 1 folder.
