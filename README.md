# 📊 FP20 Analytics Challenge #35  
## B2B Sales Pipeline Performance Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Analytics](https://img.shields.io/badge/Focus-Data%20Analytics-blue)
![Status](https://img.shields.io/badge/Project-Dashboard-green)

This repository contains my submission for **FP20 Analytics Challenge #35**.

The dashboard explores **B2B sales pipeline performance**, focusing on deal creation trends, engagement activities, and sales cycle behavior across industries and regions.

DASHBOARD PREVIEW

Link to Interactive Dashboard - [Click Here](https://app.powerbi.com/view?r=eyJrIjoiMDlhMWZlMWUtMTBjNC00ZmUwLTkyMmItNGRiNmVhMzAzYzY2IiwidCI6IjQ2NTRiNmYxLTBlNDctNDU3OS1hOGExLTAyZmU5ZDk0M2M3YiIsImMiOjl9)

![Crystal_FP20_Sales_Pipeline_Dashboard](https://github.com/user-attachments/assets/3697e530-7e77-4b8b-827b-4ba9d9d44bd9)


The objective is to understand:
- Pipeline health
- Engagement effectiveness
- Deal progression bottlenecks
- Revenue drivers
- Sales cycle patterns


# 📑 Dashboard Structure

The report consists of **three analytical pages**.



# 📈 Page 1 – Deal Creation Performance

This page focuses on **pipeline generation, deal progression, and forecasting accuracy**.

### Key KPIs

| Metric | Value |
|------|------|
| Total Pipeline Value | €1.02bn |
| Open Pipeline Value | €606M |
| Revenue | €241M |
| Deal Count | 12K |
| Won Deals | 2,999 |
| Win Rate | 25.52% |
| Forecast Accuracy | 56.12% |

### Key Insights

- Technology (€304M) and Financial Services (€272M) lead pipeline value.
- Europe dominates with €583M in pipeline.
- The deal funnel narrows significantly from 3,125 leads to 756 contracts, highlighting major drop-offs during negotiation and closing.

### Visual Analysis

- Pipeline Value by Industry
- Pipeline Value by Region
- Open Pipeline by Sales Rep Seniority
- Stage Funnel Analysis
- Forecast vs Revenue Trend



# 🤝 Page 2 – Activity & Engagement Trends

This page analyzes **sales engagement patterns and rep activity levels**.

### Key KPIs

| Metric | Value |
|------|------|
| Total Pipeline Value | €1.02bn |
| Total Activities | 118K |
| Activities per Deal | 10 |
| Days Since Last Activity | 35 |
| Avg Activity Duration | 40 mins |

### Key Insights

- Email dominates engagement (73K activities), followed by calls and meetings.
- Sales teams average 10 activities per deal.
- Average inactivity of 35 days indicates possible pipeline stagnation risks.
- Rep engagement is relatively consistent, with top performers leading activity volumes.

### Visual Analysis

- Activities per Deal vs Win Rate by Role
- Activity Type Breakdown
- Activities by Rep
- Monthly Activity Trend



# ⏳ Page 3 – Sales Cycle & Segmentation

This page examines **deal velocity, segmentation, and revenue drivers**.

### Sales Cycle Distribution

| Cycle Bucket | Deals |
|--------------|------|
| 365+ Days | ~421 |
| 181–365 Days | ~208 |
| 91–180 Days | ~132 |
| 31–90 Days | ~59 |
| 0–30 Days | ~17 |

Average sales cycle: **~131 days**

### Revenue by Product

| Product Category | Revenue |
|-----------------|--------|
| Cloud Migration | €56M |
| Professional Services | €39M |
| Integration Services | €38M |
| Data Platform | €37M |
| Analytics & BI | €36M |
| Security | €34M |

### Industry Performance

| Industry | Revenue | Win Rate | Avg Deal Value | Avg Cycle |
|---------|--------|--------|--------|--------|
| Technology | €714M | 24.69% | €179K | ~132 days |
| Retail & E-commerce | €234M | 24.39% | €54K | ~131 days |
| Manufacturing | €166M | 25.80% | €46K | ~129 days |
| Logistics | €191M | 24.28% | €51K | ~128 days |

### Key Insights

- Nearly half of deals exceed 180 days, indicating long sales cycles.
- Technology dominates revenue but comes with longer deal timelines.
- Manufacturing shows efficient performance with shorter cycles and strong win rates.



# 🧩 Data Model

The dashboard follows a **star schema design**.

### Fact Tables
- FactDeals
- FactActivities

### Dimension Tables
- DimCompany
- DimSalesRep
- DimDate

Relationships enable analysis across:
- Deal creation timelines
- Activity engagement timelines
- Industry and regional segmentation



# 🧮 Key Measures

The report includes several DAX measures such as:

- Total Pipeline Value
- Open Pipeline Value
- Revenue
- Deal Count
- Won Deals
- Win Rate
- Forecast Value
- Forecast Accuracy
- Activities per Deal
- Total Activities
- Avg Activity Duration
- Avg Sales Cycle
- Product Win Rate
- Revenue MTD / Revenue YTD

The DAX Measure Excel file is included in the repository.

# 🎯 Strategic Takeaways

- Improve forecast accuracy beyond 56%
- Focus sales coaching on late-stage deal progression
- Increase higher-impact engagement activities such as demos and workshops
- Reduce long sales cycles in large enterprise deals
- Expand growth opportunities in Asia-Pacific



# 🛠 Tools Used

- Power BI  
- DAX  
- Data Modeling  
- Data Visualization
- Figma and Power Point
- Excel 



# 👩‍💻 Author

Crystal Andrea Dsouza  
Bachelor of Accounting & Finance  
St. Xavier's College, Mumbai

