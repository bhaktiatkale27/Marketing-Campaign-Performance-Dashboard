# Marketing Campaign Performance Dashboard

## 📊 Project Overview

The **Marketing Campaign Performance Dashboard** is an Excel-based data analysis and visualization project designed to evaluate digital marketing campaign performance across different **channels, regions, and time periods**.

The project transforms campaign-level marketing data into calculated performance metrics, PivotTables, charts, KPI cards, and interactive filters. The dashboard helps identify which channels and regions generate stronger revenue, conversions, profit, and return on advertising spend.

---

## 🎯 Business Objective

The main objectives of this project are to:

- Monitor marketing campaign performance across channels and regions.
- Compare **spend, revenue, profit, and conversions**.
- Measure campaign efficiency using **CTR, CPC, CPA, ROAS, and Profit Margin**.
- Analyze campaign performance over time.
- Identify high-performing and under-performing channels.
- Understand regional conversion and profitability patterns.
- Build an interactive Excel dashboard for decision-making.

---

## 📁 Dataset

The analysis is based on the `MARKETING_CAMPAIGN_PERFORMANCE_ANALYSIS.xlsx` workbook (sheets: `Raw Data`, `Cleaned Data`, `PivoteTables`, `DashBoard`).

### Dataset Summary

| Item | Value |
|---|---:|
| Campaigns | 500 |
| Channels | 5 |
| Regions | 4 |
| Date Range | 10 Dec 2024 – 10 Jun 2025 |
| Total Budget | $3,311,673.01 |
| Total Spend | $3,132,508.19 |
| Total Revenue | $6,552,948.08 |
| Total Profit | $3,420,439.89 |
| Overall ROAS | 2.09 |
| Total Impressions | 62,386,067 |
| Total Clicks | 1,814,121 |
| Total Conversions | 184,526 |

### Channels

- Facebook
- Google Ads
- Instagram
- LinkedIn
- Twitter

### Regions

- East
- North
- South
- West

---

## 🧹 Data Preparation

The project includes the following data preparation steps:

1. Reviewed the structure and data types of the campaign dataset.
2. Checked for duplicate records.
3. Checked for missing values.
4. Standardized date and numeric/currency formatting.
5. Created calculated marketing performance columns.
6. Created a Year-Month field for time-based analysis.
7. Built PivotTables for channel, region, monthly, and conversion analysis.

### Data Quality Result

The final campaign records contain:

- **500 unique campaign IDs**
- **No duplicate campaign records**
- **No missing values in the 500 campaign records**
- **5 marketing channels**
- **4 regions**

> Note: The workbook's `Cleaned Data` sheet contains a few blank rows below the 500 campaign records. These blank rows are not treated as campaign records in the analysis.

---

## 🧮 Calculated Metrics

The following metrics were used in the analysis:

| Metric | Formula | Purpose |
|---|---|---|
| CTR | Clicks / Impressions | Measures click engagement |
| CPC | Spend / Clicks | Measures cost per click |
| CPA | Spend / Conversions | Measures cost per acquisition/conversion |
| ROAS (campaign level) | Revenue / Spend | Measures revenue generated per unit of advertising spend for a single campaign |
| ROAS (aggregate) | SUM(Revenue) / SUM(Spend) | Used for every channel, region, month and KPI-card result. In PivotTables this is a **Calculated Field** (`ROAS_Agg`) |
| Profit | Revenue - Spend | Measures campaign profitability |
| Profit Margin % | Profit / Revenue | Measures profitability as a percentage |
| Year-Month | Extracted from Date | Enables monthly trend analysis |

### Overall Calculated Performance

| KPI | Actual Result |
|---|---:|
| CTR | 2.91% |
| CPC | $1.73 |
| CPA | $16.98 |
| ROAS | 2.09 |
| Profit | $3,420,439.89 |
| Profit Margin | 52.20% |
| Budget Utilization | 94.59% |
| Unused Budget | $179,164.82 |

---

# 📌 Dashboard Components

The Excel dashboard contains the following major components:

### KPI Cards

- Total Spend
- Total Revenue
- Total Profit
- ROAS (aggregate: Total Revenue ÷ Total Spend = 2.09)
- Total Conversions

### Visualizations

1. **Spend vs Revenue Over Time**
2. **Channel-wise ROAS**
3. **Region-wise Conversions**
4. **Budget Allocation by Channel**
5. **Campaign Performance by Channel**
6. **Campaign Conversion Funnel**

### Interactive Filters

- Channel
- Region
- Year-Month / Date filter

These filters are intended to allow users to analyze the dashboard for specific channels, regions, and time periods.

---

# 📈 Actual Dashboard Results

## 1. Overall Performance

The campaigns generated **$6,552,948.08 in revenue** from **$3,132,508.19 in advertising spend**, resulting in **$3,420,439.89 profit**.

The overall **ROAS was 2.09**, meaning that approximately **$2.09 of revenue was generated for every $1 spent**.

The campaign set produced **184,526 conversions** from **1,814,121 clicks** and **62,386,067 impressions**.

The total spend used approximately **94.59% of the available budget**, leaving **$179,164.82 unspent**.

---

# 🔎 Real Insights & Findings

## 🥇 1. Instagram was the strongest overall channel

Instagram delivered the strongest overall performance among the five channels.

- Revenue: **$1,413,738.00**
- Profit: **$796,939.27**
- Conversions: **39,603**
- ROAS: **2.29**
- CPA: **$15.57**

Instagram also had the **highest ROAS** and **lowest CPA** among the five channels.

**Finding:** Instagram provides the best combination of revenue generation, conversion volume, profitability, and advertising efficiency in this dataset.

---

## ⚠️ 2. Twitter was the weakest-performing channel

Twitter had the lowest overall efficiency:

- Revenue: **$1,193,639.25**
- Profit: **$539,857.69**
- Conversions: **34,412**
- ROAS: **1.83**
- CPA: **$19.00**
- Profit Margin: **45.23%**

Twitter recorded the **lowest ROAS** and **highest CPA** among the channels.

**Finding:** Twitter should be reviewed for campaign targeting, creative performance, audience quality, and spending efficiency before increasing its budget.

---

## 📊 3. Instagram generated the highest profit

Instagram generated approximately **$796,939.27 in profit**, the highest among all channels.

Google Ads generated the second-highest profit at approximately **$734,266.18**.

**Finding:** Instagram and Google Ads are the strongest channels from a profit-generation perspective.

---

## 💰 4. Budget allocation was relatively balanced

Budget allocation was distributed across all five channels rather than being concentrated in one channel.

Approximate budget shares were:

- Facebook: **18.41%**
- Google Ads: **19.89%**
- Instagram: **19.81%**
- LinkedIn: **20.81%**
- Twitter: **21.08%**

**Finding:** The budget was fairly evenly distributed, but performance varied noticeably. This suggests that future budget allocation could be more performance-driven.

---

## 🌍 5. West was the strongest region

West recorded the highest:

- Conversions: **48,707**
- Revenue: **$1,752,564.19**
- Profit: **$941,844.40**
- ROAS: **2.16**

West generated the highest conversion volume and the highest regional ROAS (2.162), only marginally ahead of South (2.155).

**Finding:** West is the strongest region in the dataset and could be considered a priority region for maintaining or expanding effective campaigns.

---

## 🟢 6. South also showed strong performance

South generated:

- **47,588 conversions**
- **$1,662,610.72 revenue**
- **$891,200.64 profit**
- **2.16 ROAS**

Its ROAS was close to West and its CPA was **$16.21**.

**Finding:** South is another strong-performing region and shows good potential for continued investment.

---

## 📉 7. North had high activity but lower efficiency than West and South

North had:

- **46,771 conversions**
- **$1,706,679.86 revenue**
- **$868,004.42 profit**
- **2.03 ROAS**
- **$17.93 CPA**

North produced substantial campaign volume, but its CPA was higher than the other regions.

**Finding:** North should be monitored for cost efficiency, especially when compared with West and South.

---

## 📅 8. Monthly ROAS changed considerably

The monthly ROAS values were:

- **2024-12**: 1.73
- **2025-01**: 2.33
- **2025-02**: 2.27
- **2025-03**: 2.15
- **2025-04**: 1.89
- **2025-05**: 2.06
- **2025-06**: 2.60

The lowest monthly ROAS was **1.73 in 2024-12**, while the highest was **2.60 in 2025-06**.

**Important:** June contains only **24 campaign records** and the dataset ends on **10 June 2025**, so the June ROAS should **not be interpreted as a full-month result**.

**Finding:** Campaign efficiency improved substantially after December, but monthly results fluctuate and should be monitored over time.

---

## 📢 9. Overall campaign engagement was positive

The overall CTR was **2.91%**, meaning approximately **2.91% of impressions resulted in clicks**.

The overall CPC was **$1.73**, while CPA was **$16.98**.

**Finding:** The dashboard can be used to monitor whether increased traffic and engagement are translating into conversions efficiently.

---

## 💡 10. Budget was not fully utilized

Total available budget was **$3,311,673.01**, while actual spend was **$3,132,508.19**.

This left approximately **$179,164.82 unspent**, with a budget utilization rate of **94.59%**.

**Finding:** There is some remaining budget capacity. However, additional spending should be prioritized toward channels and regions demonstrating stronger ROAS and lower CPA rather than distributed equally.

---

# 📋 Channel Performance

| Channel | Budget | Spend | Revenue | Profit | Conversions | ROAS | CTR | CPA |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Instagram | $655,972.10 | $616,798.73 | $1,413,738.00 | $796,939.27 | 39,603 | 2.29 | 2.84% | $15.57 |
| Google Ads | $658,766.93 | $637,608.50 | $1,371,874.68 | $734,266.18 | 38,479 | 2.15 | 2.94% | $16.57 |
| LinkedIn | $689,111.07 | $652,119.29 | $1,287,791.22 | $635,671.93 | 36,570 | 1.97 | 2.84% | $17.83 |
| Facebook | $609,756.67 | $572,200.11 | $1,285,904.93 | $713,704.82 | 35,462 | 2.25 | 3.17% | $16.14 |
| Twitter | $698,066.24 | $653,781.56 | $1,193,639.25 | $539,857.69 | 34,412 | 1.83 | 2.78% | $19.00 |

---

# 🌎 Region Performance

| Region | Spend | Revenue | Profit | Conversions | ROAS | CPA |
|---|---:|---:|---:|---:|---:|---:|
| West | $810,719.79 | $1,752,564.19 | $941,844.40 | 48,707 | 2.16 | $16.64 |
| South | $771,410.08 | $1,662,610.72 | $891,200.64 | 47,588 | 2.16 | $16.21 |
| North | $838,675.44 | $1,706,679.86 | $868,004.42 | 46,771 | 2.03 | $17.93 |
| East | $711,702.88 | $1,431,093.31 | $719,390.43 | 41,460 | 2.01 | $17.17 |

---

# 📅 Monthly Performance

| Month | Spend | Revenue | Profit | ROAS | Conversions |
|---|---:|---:|---:|---:|---:|
| 2024-12 | $387,223.67 | $669,060.35 | $281,836.68 | 1.73 | 18,177 |
| 2025-01 | $451,320.34 | $1,049,410.80 | $598,090.46 | 2.33 | 28,935 |
| 2025-02 | $519,247.21 | $1,178,268.76 | $659,021.55 | 2.27 | 32,571 |
| 2025-03 | $437,450.39 | $941,547.01 | $504,096.62 | 2.15 | 26,943 |
| 2025-04 | $649,014.28 | $1,226,839.00 | $577,824.72 | 1.89 | 36,584 |
| 2025-05 | $558,132.99 | $1,149,303.78 | $591,170.79 | 2.06 | 32,256 |
| 2025-06 | $130,119.31 | $338,518.38 | $208,399.07 | 2.60 | 9,060 |

---

# 📊 Dashboard Visuals Explained

## Spend vs Revenue Over Time

A line chart compares monthly advertising spend against monthly revenue.

**Purpose:** Identify periods where revenue increases faster or slower than marketing spend.

---

## Channel-wise ROAS

A channel comparison is used to evaluate return on advertising spend.

**Purpose:** Identify which channels generate the strongest revenue relative to spend.

**Key result:** Instagram has the highest aggregate ROAS at **2.29**, while Twitter has the lowest at **1.83**.

> ROAS for channel-level findings is calculated as **total channel revenue ÷ total channel spend**, using the PivotTable calculated field `ROAS_Agg` (`='Revenue ($)'/'Spend ($)'`). The PivotTable default "Sum of ROAS" must **not** be used, because it adds up campaign-level ROAS values and gives meaningless totals (for example 231 to 247 per channel) and a wrong channel ranking.

| Rank | Channel | ROAS |
|---:|---|---:|
| 1 | Instagram | 2.29 |
| 2 | Facebook | 2.25 |
| 3 | Google Ads | 2.15 |
| 4 | LinkedIn | 1.97 |
| 5 | Twitter | 1.83 |

---

## Region-wise Conversions

A column/bar chart compares conversions across East, North, South, and West.

**Purpose:** Identify regions generating the highest number of conversions.

**Key result:** West generated the highest number of conversions at **48,707**.

---

## Budget Allocation by Channel

A pie chart shows the share of total budget assigned to each channel.

**Purpose:** Understand how the available marketing budget is distributed.

---

## Campaign Performance by Channel

A clustered column chart compares:

- Impressions
- Clicks
- Conversions

across the five channels.

**Purpose:** Compare campaign activity and conversion volume across marketing channels.

---

## Campaign Conversion Funnel

The overall campaign funnel is:

**Impressions → Clicks → Conversions**

| Funnel Stage | Total |
|---|---:|
| Impressions | 62,386,067 |
| Clicks | 1,814,121 |
| Conversions | 184,526 |

**Purpose:** Show how the campaign audience moves from exposure to engagement and finally to conversion.

---

# 🛠️ Tools & Technologies

- **Microsoft Excel / WPS Office**
- Excel formulas
- PivotTables
- PivotCharts
- Slicers / filters
- Dashboard design
- Data cleaning and transformation
- Marketing KPI analysis

---

# 📂 Workbook Structure

| Sheet | Purpose |
|---|---|
| `Raw Data` | Original campaign dataset |
| `Cleaned Data` | Cleaned data with calculated KPI columns |
| `PivoteTables` | PivotTables used for dashboard analysis |
| `DashBoard` | Final interactive marketing dashboard |

---

# 🔄 Project Workflow

```text
Raw Marketing Data
        ↓
Data Understanding
        ↓
Data Cleaning
        ↓
Calculated KPI Columns
        ↓
PivotTables
        ↓
PivotCharts
        ↓
Dashboard
        ↓
Insights & Findings
        ↓
Business Recommendations
```

---

# 💼 Business Recommendations

Based on the actual dataset:

1. **Prioritize Instagram** because it has the highest ROAS, highest conversions, highest revenue, and highest profit among the channels.
2. **Review Twitter performance** because it has the lowest ROAS and highest CPA.
3. **Continue monitoring Google Ads** because it generates high revenue, profit, and conversion volume.
4. **Maintain focus on West and South** because both regions show strong conversion and ROAS performance.
5. **Review North's cost efficiency** because its CPA is relatively high.
6. **Use performance-based budget allocation** instead of distributing budget equally across channels.
7. **Monitor monthly performance continuously**, especially because the dataset contains partial months such as December 2024 and June 2025.
8. **Use the dashboard filters** to investigate individual channels, regions, and months before making budget decisions.

---

# ⚠️ Important Data Interpretation Notes

- The dataset contains **500 actual campaign records**.
- June 2025 is a **partial month**, ending on 10 June 2025.
- December 2024 is also a partial period beginning on 10 December 2024.
- Aggregate ROAS should be calculated as **total revenue / total spend**, not as a sum of campaign-level ROAS values. Do not use the PivotTable's "Sum of ROAS" for the dashboard charts or KPI cards; use the `ROAS_Agg` calculated field.
- West and South have almost identical ROAS (2.162 vs 2.155); West leads by a very small margin.
- The sheet name `PivoteTables` is spelled as it appears in the workbook.
- Impressions, clicks, and conversions are **counts**, not currency values.
- The dashboard should be interpreted together with the filters and supporting KPI charts rather than relying on a single metric.

---

# ✅ Conclusion

The Marketing Campaign Performance Dashboard provides a consolidated view of campaign performance across channels, regions, and time periods.

The actual results show that **Instagram is the strongest overall channel**, while **Twitter requires the most performance attention**. At the regional level, **West is the strongest region**, followed by **South**. Overall campaigns generated **$6,552,948.08 revenue and $3,420,439.89 profit from $3,132,508.19 spend**, with an overall **ROAS of 2.09**.

The dashboard enables users to move from high-level KPIs to detailed channel, regional, and monthly analysis, supporting more informed marketing budget and campaign decisions.
