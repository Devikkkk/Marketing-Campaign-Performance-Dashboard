# 📐 KPI Definitions & Formula Reference

## Overview

This document defines all six KPI metrics engineered from the raw campaign dataset. Each KPI is calculated using Excel formulas applied in the **Cleaned Data & KPIs** sheet of the workbook.

---

## KPI Formula Reference

### 1. CTR — Click-Through Rate

| Property | Detail |
|---|---|
| **Formula** | `= Clicks / Impressions` |
| **Excel Formula** | `=H2/G2` |
| **Format** | Percentage (0.00%) |
| **Purpose** | Measures how often people click an ad after seeing it |
| **Good Benchmark** | > 2% is considered strong for digital campaigns |

**Interpretation:** A high CTR means the ad creative and targeting are effective. A low CTR may indicate poor ad relevance or weak targeting.

---

### 2. CPC — Cost Per Click

| Property | Detail |
|---|---|
| **Formula** | `= Spend / Clicks` |
| **Excel Formula** | `=F2/H2` |
| **Format** | Currency ($#,##0.00) |
| **Purpose** | Measures the average cost incurred for each click |
| **Goal** | Lower is better — indicates cost-efficient ad delivery |

**Interpretation:** A rising CPC may indicate increased competition in the ad auction or poor Quality Score. Lower CPC with high CTR = efficient campaign.

---

### 3. CPA — Cost Per Acquisition

| Property | Detail |
|---|---|
| **Formula** | `= Spend / Conversions` |
| **Excel Formula** | `=F2/I2` |
| **Format** | Currency ($#,##0.00) |
| **Purpose** | Measures the average cost to acquire one customer action |
| **Goal** | Should be lower than the average revenue per conversion |

**Interpretation:** CPA is the most business-critical efficiency metric. If CPA exceeds average revenue per conversion, the campaign is unprofitable at the unit level.

---

### 4. ROAS — Return on Ad Spend

| Property | Detail |
|---|---|
| **Formula** | `= Revenue / Spend` |
| **Excel Formula** | `=J2/F2` |
| **Format** | Number (0.00) |
| **Purpose** | Measures revenue generated for every $1 spent on advertising |
| **Good Benchmark** | ROAS > 2.0x is generally considered profitable |

**Interpretation:** A ROAS of 2.09 means every $1 spent returned $2.09 in revenue. ROAS below 1.0 means the campaign is losing money.

---

### 5. Profit

| Property | Detail |
|---|---|
| **Formula** | `= Revenue − Spend` |
| **Excel Formula** | `=J2-F2` |
| **Format** | Currency ($#,##0.00) |
| **Purpose** | Measures net financial gain from the campaign |
| **Goal** | Maximise profit across all channels and regions |

**Interpretation:** Profit gives an absolute measure of campaign financial performance. It should be tracked alongside ROAS for a complete picture.

---

### 6. Profit Margin %

| Property | Detail |
|---|---|
| **Formula** | `= (Profit / Revenue) × 100` |
| **Excel Formula** | `=(P2/J2)*100` |
| **Format** | Percentage (0.0%) |
| **Purpose** | Expresses profit as a proportion of revenue generated |
| **Good Benchmark** | > 40% margin indicates strong campaign profitability |

**Interpretation:** Profit Margin % allows fair comparison across campaigns of different sizes. A small campaign with 60% margin may be more efficient than a large one with 30% margin.

---

## Summary Table

| KPI | Formula | Format | Lower = Better? |
|---|---|---|---|
| CTR | Clicks / Impressions | % | ❌ Higher is better |
| CPC | Spend / Clicks | $ | ✅ Lower is better |
| CPA | Spend / Conversions | $ | ✅ Lower is better |
| ROAS | Revenue / Spend | x | ❌ Higher is better |
| Profit | Revenue − Spend | $ | ❌ Higher is better |
| Profit Margin % | (Profit / Revenue) × 100 | % | ❌ Higher is better |

---

## Dataset Column Mapping (Excel Sheet: Cleaned Data & KPIs)

| Column Letter | Column Name |
|---|---|
| A | Campaign_ID |
| B | Date |
| C | Year-Month |
| D | Channel |
| E | Region |
| F | Budget ($) |
| G | Spend ($) |
| H | Impressions |
| I | Clicks |
| J | Conversions |
| K | Revenue ($) |
| L | CTR |
| M | CPC ($) |
| N | CPA ($) |
| O | ROAS |
| P | Profit ($) |
| Q | Profit Margin % |

---

*KPI Reference — Marketing Campaign Performance Dashboard*
*Author: Devik Satya Venkat Balabhadruni*
