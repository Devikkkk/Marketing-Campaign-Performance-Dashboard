# 📋 Project Brief — Marketing Campaign Performance Dashboard

## Business Context

Marketing teams invest heavily in multi-channel campaigns (Google Ads, Facebook, Twitter, LinkedIn, Instagram) to reach their audience and drive revenue. However, raw campaign data lacks business value unless transformed into clear, actionable insights.

Without a structured reporting framework, stakeholders cannot:
- Identify which channels are delivering the best return on investment
- Compare regional performance to allocate budgets effectively
- Monitor trends over time to make proactive campaign decisions
- Track efficiency metrics such as cost-per-click or cost-per-acquisition

---

## Business Objective

- Track the performance of marketing campaigns across platforms and regions
- Analyse profitability, efficiency, and return on ad spend
- Monitor key KPIs: Click-Through Rate, Cost Per Click, Conversions, and ROAS
- Build an interactive Excel Dashboard for real-time stakeholder decision-making

---

## Problem Statement

Transform 500 rows of raw marketing campaign data into a comprehensive Excel dashboard using advanced Excel techniques. The goal is to enable stakeholders to monitor performance, identify underperforming channels, and optimise marketing investments.

---

## Dataset

| Column | Description |
|---|---|
| Campaign_ID | Unique campaign identifier |
| Date | Date of campaign activity |
| Channel | Marketing platform (Google Ads, Facebook, Twitter, LinkedIn, Instagram) |
| Region | Geographic region (East, North, South, West) |
| Budget ($) | Budget allocated |
| Spend ($) | Actual spend |
| Impressions | Number of ad views |
| Clicks | Number of clicks on ads |
| Conversions | Customer actions (sign-ups/purchases) |
| Revenue ($) | Revenue generated from the campaign |

---

## Project Workflow

### Step 1 — Data Understanding
- Review structure, data types, and campaign lifecycle
- Distinguish categorical (Channel, Region) vs numerical (Spend, Revenue, etc.) columns
- Confirm date range and record volume

### Step 2 — Data Cleaning & Preprocessing
- Remove duplicate records
- Fix formatting in columns (numeric currency columns, date format standardisation)
- Check for null values and handle as needed

### Step 3 — Data Transformation
Create new calculated KPI columns:

| KPI | Formula |
|---|---|
| CTR (Click-Through Rate) | = Clicks / Impressions |
| CPC (Cost Per Click) | = Spend / Clicks |
| CPA (Cost Per Acquisition) | = Spend / Conversions |
| ROAS (Return on Ad Spend) | = Revenue / Spend |
| Profit | = Revenue − Spend |
| Profit Margin % | = (Profit / Revenue) × 100 |

Extract Year-Month from Date column for monthly trend analysis.

### Step 4 — PivotTable Analysis
Build summary pivot tables:
- Channel-wise performance (Revenue, Profit, ROAS, CTR)
- Region-wise conversions and revenue
- Monthly Spend vs Revenue trend

### Step 5 — Dashboard Development
Build an interactive Excel dashboard with:

**KPI Cards:**
- Total Revenue, Total Profit, Total Conversions
- Average ROAS, Average CTR, Profit Margin %

**Visualisations:**
- Line Chart: Monthly Spend vs Revenue trend
- Column Chart: Channel-wise ROAS comparison
- Horizontal Bar: Region-wise Conversions
- Pie Chart: Budget allocation by channel

**Filters / Slicers:**
- Channel slicer
- Region slicer
- Date range filter

---

## Deliverables

| Deliverable | Description |
|---|---|
| `Marketing_Campaign_Dashboard.xlsx` | Final 5-sheet Excel workbook with dashboard |
| `Marketing_Campaign_Data.xlsx` | Raw dataset (500 records) |
| `README.md` | Full project documentation |
| `KPI_Definitions.md` | KPI formula reference guide |
| `Insights_and_Recommendations.md` | Key findings and business recommendations |

---

## Tools Used

- Microsoft Excel (Advanced PivotTables, Slicers, KPI Metrics, Charts, Data Transformation)
- Data Cleaning & Preprocessing techniques
- Dashboard design and visual storytelling

---

*Project completed as part of MSc Data Science portfolio — Devik Satya Venkat Balabhadruni*
