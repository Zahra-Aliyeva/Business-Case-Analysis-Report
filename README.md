# Business-Case-Analysis-Report

# Marketing Performance Analysis — July–December 2024 vs. July–December 2025

## Business Question
Did marketing performance improve between July–December 2024 and the same period in 2025, and what factors might explain the change?

## Overview
This project walks through a complete marketing performance case study: KPI selection, SQL-based data extraction, root-cause analysis, dashboard visualization, and a written summary with concrete recommendations.

## KPIs Selected
- **Conversion Rate** — how effectively sessions turn into conversions
- **ROAS (Return on Ad Spend)** — revenue generated per dollar of marketing spend
- **CPA (Cost per Acquisition)** — average marketing cost per conversion
- **Revenue** — total revenue generated from marketing activity
- **Channel Mix %** — how sessions are distributed across channels

Together these KPIs cover overall performance, marketing efficiency, and channel distribution. They were compared across channels, regions, campaigns, and matching months in 2024 vs. 2025 to rule out misleading conclusions caused by seasonality or channel-mix shifts.

## Data Extraction (SQL)
Five queries form the backbone of the analysis: overall year-over-year performance, conversion rate by channel, channel mix by year, same-month year-over-year comparison, and regional performance by channel.

📄 [SQL queries](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%202.sql)

## Root-Cause Analysis
Key findings:
- Overall conversion rate rose from **5.71%** (2024) to **5.95%** (2025)
- Every channel improved on its own: Email (6.48% → 6.76%), Organic Search (8.23% → 8.57%), Paid Search (4.74% → 4.94%), Paid Social (3.07% → 3.18%)
- No Simpson's Paradox — the aggregate trend matches the channel-level trend
- Channel mix stayed nearly unchanged between the two years, so a mix-shift does not explain the gain
- All six months (July–December) showed a higher conversion rate in 2025 versus the same month in 2024, ruling out a seasonal explanation
- No standout regional outlier

📄 [Root-cause analysis](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%203)

## Visualization
The dashboard breaks performance down by channel, region, and month, with each chart tied to a specific claim from the analysis.

🖼️ [Dashboard screenshot](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Screenshot%20checkpoint%204.png)
📊 [Full Power BI dashboard (.pbix)](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%204.pbix)

## Findings Summary
The improvement is broad-based rather than narrow. The overall conversion rate climbed from 5.71% to 5.95%, and the gain shows up across every channel and every month in the comparison window, with no single region driving it. Channel mix held steady, so the result reflects genuine efficiency gains rather than a shift toward higher-converting channels.

📄 [Full written summary](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%205)

## Recommendations
1. **Improve Paid Social conversion.** Paid Social sits at the bottom of the four channels (3.07% → 3.18%). Target: raise it to at least 3.5% in the next reporting period by testing new audiences, creatives, and landing pages before scaling budget.
2. **Protect Organic Search and Email performance.** These two channels lead at 8.57% and 6.76% respectively. Keep current investment levels and use their performance as the benchmark when evaluating the rest of the channel mix.

📄 [Recommendations](https://github.com/Zahra-Aliyeva/Business-Case-Analysis-Report/blob/main/Checkpoint%206)

## Tools Used
SQL (PostgreSQL/SQLite syntax), Power BI Desktop, Excel / Google Sheets

## Repository Structure
```
├── Checkpoint 2.sql                # SQL extraction & aggregation queries
├── Checkpoint 3                    # Root-cause analysis write-up
├── Checkpoint 4.pbix               # Power BI dashboard file
├── Screenshot checkpoint 4.png     # Dashboard screenshot
├── Checkpoint 5                    # Written summary
├── Checkpoint 6                    # Actionable recommendations
└── README.md
```
