# E-Commerce Conversion Rate

## Overview
This project analyzes E-Commerce Customer Behavior data using Python to identify conversion patterns, membership-wise satisfaction rates, city-wise performance, and the impact of discounts on customer conversion.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Dataset
| Field | Details |
|-------|---------|
| Name | E-Commerce Customer Behavior |
| Source | Kaggle |
| File | E-commerce Customer Behavior.csv |
| Records | 350 rows | 11 columns |

## Project Description
The dataset contains E-Commerce customer records including Gender, Age, City, Membership Type, Total Spend, Items Purchased, Average Rating, Discount Applied, Days Since Last Purchase, and Satisfaction Level. The notebook performs data cleaning, conversion rate calculation, and visualization to identify which customer segments convert the most and what factors influence satisfaction.

## Visualizations
| # | Chart | Type | Description |
|---|-------|------|-------------|
| 1 | Conversion Rate by Membership Type | Bar Chart | Compares conversion % across Gold, Silver, Bronze members |
| 2 | Conversion Rate by City | Bar Chart | Shows which cities have highest conversion rates |
| 3 | Conversion Rate by Gender | Bar Chart | Compares Male vs Female conversion rates |
| 4 | Discount vs No Discount | Bar Chart | Impact of discounts on conversion rate |
| 5 | Overall Conversion Distribution | Pie Chart | Percentage split of Converted vs Not Converted |

## Key Findings
| Finding | Result |
|---------|--------|
| Total Customers | 350 |
| Total Converted | 125 |
| Overall Conversion Rate | 35.71% |
| Best Membership Type | Gold (100%) |
| Best Converting City | New York (100%) |
| Male Conversion Rate | 38.29% |
| Female Conversion Rate | 33.14% |
| No Discount Conversion Rate | 37.71% |
| With Discount Conversion Rate | 33.71% |
| Average Total Spend | $845.38 |
| Average Customer Rating | 4.02 |

## How to Run
1. Open the notebook in Google Colab
2. Upload the E-commerce Customer Behavior.csv dataset
3. Run Cell 1 — Import Libraries
4. Run Cell 2 — Load Dataset
5. Run all remaining cells to reproduce the analysis

## Author
**Lanke Yamini**
