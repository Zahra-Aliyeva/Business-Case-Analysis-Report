# Business-Case-Analysis-Report

# Marketing Performance Case Study — July–December 2024 vs. 2025

## Overview

This project looks at marketing performance between July–December 2024 and the same period in 2025.

The main question was whether performance actually improved and what was behind the change. I looked at overall results first, then compared channels, channel mix, months, and regions to make sure the result was not caused by a mix shift or seasonality.

## KPIs

I used five main metrics for the analysis:

- **Conversion Rate** — measures how many sessions resulted in conversions
- **ROAS** — measures revenue generated from marketing spend
- **CPA** — measures the average cost of acquiring a conversion
- **Revenue** — measures revenue generated from marketing activity
- **Channel Mix %** — shows how sessions were distributed across channels

## SQL Analysis

I used SQL to extract and compare the data needed for the analysis. The queries covered:

- Overall marketing performance by year
- Conversion rate by channel
- Channel mix by year
- Conversion rate for the same months across 2024 and 2025
- Conversion rate by region and channel

[View SQL queries](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%202.sql)

## Key Findings

The overall conversion rate increased from **5.71% in 2024 to 5.95% in 2025**.

The improvement was also visible across all four channels:

- **Email:** 6.48% → 6.76%
- **Organic Search:** 8.23% → 8.57%
- **Paid Search:** 4.74% → 4.94%
- **Paid Social:** 3.07% → 3.18%

I also checked the channel mix, and it remained almost unchanged between the two years. This means the improvement was not mainly caused by a large shift in traffic between channels.

For seasonality, I compared each month with the same month in the previous year. Conversion rate was higher in every month from July through December in 2025.

The regional results were also relatively consistent, with no single region standing out as the main reason for the overall change.

[View root-cause analysis](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%203)

## Dashboard

I created a Power BI dashboard to present the main findings visually. The visuals focus on the overall conversion rate, channel performance, channel mix, and monthly comparison between the two years.

[Dashboard screenshot](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Screenshot%20checkpoint%204.png)

[Power BI dashboard](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%204.pbix)

## Summary

The analysis shows that marketing performance improved in 2025. The increase was consistent across all channels and months, while the channel mix remained stable.

Based on the results, the improvement does not appear to be driven by one particular channel, region, or seasonal period.

[View written summary](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%205)

## Recommendations

### 1. Improve Paid Social conversion

Paid Social has the lowest conversion rate among the four channels, increasing from **3.07% to 3.18%**. I recommend setting a target to increase its conversion rate to at least **3.5%** in the next reporting period. I would test different audiences, ad creatives, and landing pages before increasing its budget.

### 2. Maintain Organic Search and Email performance

Organic Search and Email have the highest conversion rates, at **8.57%** and **6.76%** respectively. I recommend maintaining the current investment in these channels and using their performance as a benchmark when evaluating the other channels.

[View recommendations](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%206)

## Tools

- SQL
- Power BI Desktop
- Excel / Google Sheets


├── Checkpoint 6
└── README.md
