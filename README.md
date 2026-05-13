# Marketing Budget Optimization using Linear Regression

# Project Overview

This project analyzes marketing spend data across multiple advertising channels to understand their impact on sales revenue.

The objective is to identify the most effective marketing channels, build a regression model to predict sales revenue, and recommend how future marketing budgets should be allocated.

---

# Business Problem

The company invests money in multiple marketing channels such as TV, Radio, Social Media, Search Ads, and Influencer campaigns.

The leadership team wants to:

- Understand which channels drive the highest sales
- Predict future sales revenue
- Optimize marketing budget allocation
- Improve return on marketing investment

Linear Regression was used to model the relationship between marketing spend and sales revenue.

---

# Dataset Description

The dataset contains campaign-level marketing spend and sales revenue information.

## Columns

- CampaignID
- Month
- Region
- TV_Spend
- Radio_Spend
- SocialMedia_Spend
- SearchAds_Spend
- Influencer_Spend
- Sales_Revenue

---

# Tools and Libraries Used

## Tools

- VS Code
- Jupyter Notebook
- GitHub

## Python Libraries

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

# Data Cleaning Summary

The following cleaning steps were performed:

- Checked missing values
- Filled missing SocialMedia_Spend values using mean imputation
- Checked duplicate records
- Verified data types
- Performed outlier analysis
- Generated summary statistics

---

# Exploratory Data Analysis

EDA included:

- Distribution analysis of marketing spend channels
- Distribution of sales revenue
- Scatter plots of marketing channels vs sales
- Correlation heatmap
- Outlier analysis

## Key Insights

- Search Ads showed the strongest positive correlation with sales revenue.
- Radio advertising also demonstrated strong effectiveness.
- Influencer marketing showed comparatively weaker impact.
- Some outliers existed in TV and Influencer spending.

---

# Regression Model Summary

A Multiple Linear Regression model was built using:

- TV Spend
- Radio Spend
- Social Media Spend
- Search Ads Spend
- Influencer Spend

Target Variable:

- Sales Revenue

The dataset was split into training and testing sets before model training.

---

# Model Evaluation Results

| Metric   | Value  |
| -------- | ------ |
| MAE      | 19.87  |
| MSE      | 913.16 |
| RMSE     | 30.22  |
| R² Score | 0.86   |

The model explains approximately 86% of the variation in sales revenue.

---

# Coefficient Interpretation

| Channel            | Coefficient |
| ------------------ | ----------- |
| TV Spend           | 1.45        |
| Radio Spend        | 3.41        |
| Social Media Spend | 0.70        |
| Search Ads Spend   | 2.67        |
| Influencer Spend   | 0.20        |

## Interpretation

- Radio advertising has the strongest positive relationship with sales.
- Search Ads also contribute significantly to revenue generation.
- Influencer marketing has relatively lower impact.

---

# Budget Recommendations

- Increase investment in Radio advertising.
- Allocate more budget to Search Ads.
- Maintain moderate TV advertising spend.
- Reevaluate Influencer marketing strategy.
- Improve Social Media targeting and campaign optimization.
- Collect additional customer and campaign data for deeper analysis.

---

# Project Outputs

The repository contains:

- notebook.ipynb
- requirements.txt
- dataset_source.md
- outputs/channel_coefficients.csv
- outputs/channel_effectiveness.csv
- README.md

---

# How to Run the Project

## Install Dependencies

pip install -r requirements.txt

## Clone Repository

```bash
git clone https://github.com/Sathvikaaaaaa/Marketing-budget-optimization.git

```
