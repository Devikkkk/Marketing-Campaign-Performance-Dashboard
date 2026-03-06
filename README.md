# 📊 Marketing Campaign Performance Dashboard | Excel

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)
![Records](https://img.shields.io/badge/Dataset-500%20Records-blue?style=flat)
![KPIs](https://img.shields.io/badge/KPIs-6%20Engineered-orange?style=flat)

---

## 📌 Project Overview

This project delivers a complete **end-to-end Marketing Campaign Performance Dashboard** built in Microsoft Excel. Raw multi-channel campaign data (500 records) is transformed into a fully interactive, stakeholder-ready reporting dashboard — covering KPI engineering, data cleaning, PivotTable analysis, and visual storytelling across 5 structured workbook sheets.

The project demonstrates the full data analytics workflow from raw data ingestion to executive-level reporting, aligned to **PMO governance and stakeholder reporting standards**.

---

## 🎯 Business Objective

| Goal | Description |
|---|---|
| 📈 Performance Tracking | Monitor campaign performance across all channels and regions |
| 💰 Profitability Analysis | Measure ROAS, Profit, and Profit Margin per channel |
| 🎯 Efficiency Monitoring | Track CTR, CPC, and CPA to evaluate campaign efficiency |
| 📊 Interactive Reporting | Build a dynamic dashboard for real-time stakeholder decision-making |
| 🔍 Underperformance Detection | Identify low-performing channels to optimise marketing investment |

---

## 📁 Repository Structure

```
Marketing-Campaign-Performance-Dashboard/
│
├── 📊 Marketing_Campaign_Dashboard.xlsx    # Final dashboard (5 sheets)
├── 📂 Marketing_Campaign_Data.xlsx         # Raw dataset (500 records)
├── 📄 Project_Brief.md                     # Full project brief & workflow
├── 📄 KPI_Definitions.md                   # All KPI formulas & definitions
├── 📄 Insights_and_Recommendations.md      # Key findings & business recommendations
└── 📄 README.md                            # Project documentation
```

---

## 🗂️ Dataset Overview

| Detail | Description |
|---|---|
| **File** | `Marketing_Campaign_Data.xlsx` |
| **Records** | 500 rows |
| **Channels** | Google Ads, Facebook, Twitter, LinkedIn, Instagram |
| **Regions** | East, North, South, West |
| **Date Range** | Dec 2024 – Jun 2025 |

### Column Reference

| Column | Description |
|---|---|
| Campaign_ID | Unique campaign identifier |
| Date | Date of campaign activity |
| Channel | Marketing platform |
| Region | Geographic region |
| Budget ($) | Allocated budget |
| Spend ($) | Actual spend |
| Impressions | Number of ad views |
| Clicks | Number of ad clicks |
| Conversions | Customer actions (sign-ups / purchases) |
| Revenue ($) | Revenue generated from campaign |

---

## 🛠️ Project Workflow

### 1. Data Understanding
- Reviewed data structure, column types, and campaign lifecycle
- Distinguished categorical columns (Channel, Region) from numerical (Spend, Revenue, etc.)
- Identified date range and volume of records

### 2. Data Cleaning & Preprocessing
- Removed duplicate records
- Standardised date formats and currency columns
- Checked and confirmed zero null values across all fields

### 3. Data Transformation — KPI Engineering
Six calculated KPI columns were engineered from raw data:

| KPI | Formula | Purpose |
|---|---|---|
| CTR | Clicks / Impressions | Measures ad engagement rate |
| CPC | Spend / Clicks | Cost efficiency per click |
| CPA | Spend / Conversions | Cost per customer action |
| ROAS | Revenue / Spend | Return on advertising investment |
| Profit | Revenue − Spend | Net campaign profitability |
| Profit Margin % | (Profit / Revenue) × 100 | Profitability as percentage |

### 4. PivotTable Analysis
- Channel-wise performance summary (Revenue, Profit, ROAS, CTR)
- Region-wise conversions and revenue breakdown
- Monthly trend analysis (Spend vs Revenue over time)

### 5. Dashboard Development
Built an interactive Excel dashboard with KPI cards, 4 chart visualisations, and dynamic filtering.

---

## 📊 Dashboard Features

### KPI Summary Cards
| Metric | Value |
|---|---|
| 💰 Total Revenue | $6,552,948 |
| 📈 Total Profit | $3,420,440 |
| 🎯 Total Conversions | 184,526 |
| ⚡ Average ROAS | 2.09x |
| 🖱️ Average CTR | 2.91% |
| 📊 Profit Margin | 52.2% |

### Visualisations
| Chart | Type | Purpose |
|---|---|---|
| Spend vs Revenue Trend | Line Chart | Monthly performance tracking |
| Channel ROAS Comparison | Column Chart | Identify best-performing channels |
| Region-wise Conversions | Horizontal Bar | Regional performance breakdown |
| Budget Allocation | Pie Chart | Budget distribution by channel |

### Workbook Sheets
| Sheet | Purpose |
|---|---|
| 🖥️ DASHBOARD | Interactive reporting view for stakeholders |
| 📋 Raw Data | Original 500-row dataset, formatted |
| 🔧 Cleaned Data & KPIs | Cleaned data with all 6 engineered KPI columns |
| 📊 Pivot Tables | Channel, Region & Monthly summary tables |
| 📈 Chart Data | Structured data powering all dashboard charts |

---

## 🔍 Key Insights

1. **Instagram delivers the highest total revenue** at $1.41M, making it the top-performing channel despite not having the highest budget allocation.

2. **Facebook achieves the best average ROAS at 2.54x**, meaning every $1 spent returns $2.54 in revenue — the most cost-efficient channel overall.

3. **Twitter has the lowest ROAS at 2.09x**, suggesting budget reallocation away from Twitter toward Instagram and Facebook could improve overall campaign efficiency.

4. **West region leads in both conversions (48,707) and revenue ($1.75M)**, while East region underperforms with the lowest conversion volume (41,460).

5. **Revenue grew significantly from Dec 2024 ($669K) to April 2025 ($1.23M)**, representing an 83% month-on-month growth peak — indicating strong campaign momentum in Q1–Q2 2025.

6. **Overall campaign profitability is strong** — with a 52.2% profit margin across all channels, total profit of $3.42M was generated from $3.13M in total spend.

---

## 💡 Recommendations

- **Increase Instagram & Facebook budgets** — both deliver above-average ROAS and should receive higher allocation in future campaign planning
- **Reduce Twitter spend** — consistently the lowest ROAS; reallocate to higher-performing channels
- **Invest more in the West region** — highest conversion rate and revenue, suggesting strong audience alignment
- **Investigate East region underperformance** — lowest conversions despite comparable budget allocation; may need audience targeting review
- **Sustain April–May campaign intensity** — peak revenue months; plan campaigns to capitalise on this seasonal pattern

---

## 🧰 Tools & Skills Demonstrated

| Skill | Application |
|---|---|
| **Excel Data Cleaning** | Duplicate removal, date formatting, null checks |
| **KPI Engineering** | 6 calculated metrics from raw campaign data |
| **PivotTables & Slicers** | Multi-dimensional channel, region, and time analysis |
| **Data Visualisation** | Line, bar, horizontal bar, and pie charts |
| **Dashboard Design** | KPI cards, section layout, colour-coded reporting |
| **Stakeholder Reporting** | Executive-ready dashboard aligned to PMO standards |
| **Business Analysis** | Insight generation and actionable recommendations |

---

## 👤 Author

**Devik Satya Venkat Balabhadruni**
MSc Data Science (Merit) | CMI Level 7 Strategic Management
🔗 [LinkedIn](https://www.linkedin.com/in/deviksatyavenkat)

---

## 📜 Skills Tags

`Microsoft Excel` `Data Cleaning` `KPI Development` `PivotTables` `Data Visualisation` `Dashboard Design` `Business Analysis` `Stakeholder Reporting` `Marketing Analytics` `Campaign Performance`
