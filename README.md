# Marketing_Campaign_Analysis_R
Marketing campaign performance analysis using R, statistical metrics and data visualization.

# Marketing Campaign Performance Analysis

## Project Overview

This project uses R to analyze marketing campaign performance across multiple advertising channels. The goal is to evaluate advertising efficiency, identify performance trends, and generate data-driven recommendations for marketing decisions.

## Objectives

- Evaluate Return on Ad Spend (ROAS) by marketing channel.
- Compare total revenue against advertising costs.
- Analyze Click-Through Rate (CTR) and conversion rates.
- Identify high-performing campaigns and opportunities for improvement.

## Tools and Technologies

- **Language:** R
- **Environment:** Posit Cloud / RStudio
- **Visualization:** ggplot2
- **Data Format:** CSV

## Dataset

The dataset contains 1,000 marketing campaign records and eight original variables:

- Date
- Campaign
- Channel
- Impressions
- Clicks
- Advertising Spend
- Conversions
- Revenue

The dataset includes six marketing channels and 12 campaigns. It is used for educational analysis; its source and redistribution terms should be verified before sharing the raw data.

## Methodology

1. Imported and inspected the dataset using R.
2. Calculated Return on Ad Spend (ROAS).
3. Aggregated revenue and advertising spend by channel.
4. Calculated Click-Through Rate and conversion rate.
5. Ranked channels and campaigns by performance.
6. Created visualizations to communicate findings.

## Key Performance Indicators

| Metric | Definition |
|---|---|
| ROAS | Revenue divided by advertising spend |
| CTR | Clicks divided by impressions, multiplied by 100 |
| Conversion Rate | Conversions divided by clicks, multiplied by 100 |
| Total Revenue | Sum of recorded campaign revenue |
| Total Ad Spend | Sum of recorded advertising costs |

## Preliminary Findings

Initial analysis of average row-level ROAS showed differences across channels:

- Email had an unusually high average ROAS and requires further investigation.
- Affiliate and Paid Search also showed high average row-level ROAS.
- Display had an average row-level ROAS below 1.0.

These are preliminary findings. Overall channel ROAS, calculated as total revenue divided by total advertising spend, is used for a more meaningful comparison.

## Project Files

- R script for data analysis. [Marketing Campaign Analysis](https://github.com/TarikArcher/Marketing_Campaign_Analysis_R/blob/main/campaign_revenue_results.csv)
- Marketing channel ROAS visualization. [Roas By Channel](https://github.com/TarikArcher/Marketing_Campaign_Analysis_R/blob/main/roas_by_channel.png)
- Channel-level revenue, spend, and ROAS. [channel_roas_results.csv](https://github.com/TarikArcher/Marketing_Campaign_Analysis_R/blob/main/channel_roas_results.csv)
- Revenue totals by campaign. [Campaign_Revenue_Results.csv](https://github.com/TarikArcher/Marketing_Campaign_Analysis_R/blob/main/campaign_revenue_results.csv)
- Dataset with calculated metrics. [Marketing_Analysis_Results.csv](https://github.com/TarikArcher/Marketing_Campaign_Analysis_R/blob/main/campaign_revenue_results.csv)

## Limitations

ROAS measures revenue relative to advertising spend, not profit. The analysis does not account for product costs or other operating expenses. The findings describe patterns in the available dataset and do not establish that a marketing channel caused a particular outcome.

## Future Improvements

- Create additional visualizations with ggplot2.
- Investigate unusually high ROAS values and potential outliers.
- Compare overall channel ROAS with average row-level ROAS.
- Develop actionable recommendations based on validated results.

## Author

Tarik Archer  
Data Analyst Portfolio Project
