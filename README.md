# Business-Case-Analysis-Report

# Marketing Performance Case Study — July–December 2024 vs. 2025

## Overview

This project focuses on marketing performance between July–December 2024 and the same period in 2025.

The main question was whether marketing performance improved in 2025 and what factors were behind the change. I started with the overall results and then broke them down by channel, channel mix, month, and region. This was important because an overall result can sometimes hide what is happening at a more detailed level.

## Business Question

Did marketing performance improve between July–December 2024 and the same period in 2025, and what factors may explain the change?

To answer this, I focused on five KPIs:

- **Conversion Rate** — measures how effectively sessions are converted into conversions
- **ROAS** — shows how much revenue is generated from marketing spend
- **CPA** — shows the average cost of generating one conversion
- **Revenue** — measures the total revenue generated from marketing activity
- **Channel Mix %** — shows how sessions are distributed across marketing channels

I compared the results across channels, regions, and the same months in both years to avoid drawing conclusions from the overall numbers alone.

## SQL Analysis

I used SQL to extract and aggregate the data needed for the analysis. The queries were focused on five areas:

1. Overall marketing performance by year
2. Conversion rate by channel
3. Channel mix by year
4. Same-month conversion rate comparison between 2024 and 2025
5. Regional performance by channel

I also used SQL window functions for the channel mix and same-month comparison, which helped me compare the results without relying only on overall totals.

[View SQL queries](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%202.sql)

## Key Findings

The overall conversion rate increased from **5.71% in 2024 to 5.95% in 2025**. Conversions also increased from **110,597 to 115,186**, while sessions remained almost unchanged.

When I looked at the individual channels, the improvement was consistent across all four:

- **Email:** 6.48% → 6.76%
- **Organic Search:** 8.23% → 8.57%
- **Paid Search:** 4.74% → 4.94%
- **Paid Social:** 3.07% → 3.18%

This was important because it showed that the overall improvement was not coming from only one channel.

I also checked for a possible **Simpson's Paradox** situation, where the overall result can tell a different story from the individual channel results. In this case, that pattern was not present. The overall conversion rate improved and all four channels improved as well.

The channel mix was also very stable between the two years. For example, Organic Search accounted for 29.08% of sessions in 2024 and 29.07% in 2025, while Paid Social changed only from 25.85% to 25.88%. This suggests that a major change in traffic distribution was not responsible for the improvement.

Seasonality was another point I checked. Instead of comparing December with November, I compared each month with the same month in the previous year. Conversion rate was higher in 2025 for every month from July through December. This makes the improvement more consistent and reduces the risk of drawing conclusions from normal monthly seasonality.

The regional analysis also did not show one region that was clearly responsible for the overall result. The conversion patterns were broadly similar across regions and channels.

[View root-cause analysis](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%203)

## Dashboard

I created a Power BI dashboard to present the main findings from the analysis. The visuals were selected to answer specific questions rather than simply display as much data as possible.

The dashboard includes:

- Overall conversion rate comparison between 2024 and 2025
- Conversion rate by marketing channel
- Channel mix comparison
- Monthly conversion rate comparison between the two years

The dashboard helps connect the overall result with the more detailed channel and time-level analysis.

[Dashboard screenshot](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Screenshot%20checkpoint%204.png)

[Power BI dashboard](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%204.pbix)

## Written Summary

Overall, the analysis shows that marketing performance improved during July–December 2025 compared with the same period in 2024.

The increase was not limited to one channel or one month. All four channels improved their conversion rates, the channel mix remained almost unchanged, and every comparable month performed better in 2025. Based on these results, the improvement appears to be broad rather than being caused by a single channel, region, or seasonal period.

[View written summary](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%205)

## Recommendations

### 1. Improve Paid Social conversion

Paid Social has the lowest conversion rate among the four channels, although it improved from **3.07% to 3.18%**. I recommend setting a target of at least **3.5%** for the next reporting period and testing different audiences, ad creatives, and landing pages before increasing its budget.

### 2. Maintain Organic Search and Email performance

Organic Search and Email currently have the highest conversion rates at **8.57%** and **6.76%**. I recommend maintaining the current investment in these channels and using their performance as a benchmark when evaluating changes to the other channels.

These recommendations are based on the channel-level results rather than the overall conversion rate alone.

[View recommendations](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%206)

## Tools Used

- SQL
- Power BI Desktop
- Excel 

