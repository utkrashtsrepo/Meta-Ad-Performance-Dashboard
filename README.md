# Meta Ad Performance Dashboard | SQL, Power BI

## Project Overview

The Meta Ad Performance Dashboard analyzes Facebook and Instagram advertising campaigns using SQL, Power BI, and DAX. It transforms advertising event data, campaign budgets, and audience demographics into actionable insights across the marketing funnel, from impressions and clicks to purchases.

The dashboard helps analyze campaign effectiveness, compare audience engagement, identify high-performing advertisements, and understand how campaign budgets relate to advertising outcomes.

## Objectives

- Analyze advertising performance across Meta platforms.
- Track campaign engagement and conversion metrics.
- Compare performance across age groups, genders, countries, and ad types.
- Identify high-performing campaigns and audience segments.
- Evaluate campaign budgets alongside engagement and purchase outcomes.
- Support data-driven marketing decisions through interactive visualizations.

## Tools and Technologies

- **SQL Server / SQL:** Data extraction, querying, and transformation.
- **Power BI Desktop:** Interactive dashboards and data visualization.
- **DAX:** Calculated measures and performance KPIs.
- **Power Query:** Data preparation and transformation.
- **CSV / Excel:** Source data management.

## Data Sources

The dashboard uses four CSV files representing different parts of the advertising ecosystem:

| File | Description |
|---|---|
| `ad_events.csv` | User interactions with advertisements, including clicks, shares, comments, and purchases. |
| `ads.csv` | Advertisement details, including platform, ad type, and demographic attributes. |
| `campaigns.csv` | Campaign-level information, including budgets and campaign status. |
| `users.csv` | User demographic and interest information for audience segmentation. |

## Key Performance Indicators

| Metric | Calculation / Purpose |
|---|---|
| Impressions | Total number of ad views. |
| Clicks | Total number of ad clicks. |
| Shares | Number of times ads were shared. |
| Comments | Number of comments received. |
| Purchases | Total recorded purchase events. |
| Engagements | Clicks + Shares + Comments. |
| Click-Through Rate (CTR) | (Clicks / Impressions) × 100 |
| Engagement Rate | (Engagements / Impressions) × 100 |
| Conversion Rate | (Purchases / Clicks) × 100 |
| Purchase Rate | (Purchases / Impressions) × 100 |
| Total and Average Budget | Campaign budget overview. |

*Note: Conversion rate is defined here as purchases divided by clicks. Ensure the DAX measures follow the same definition.*

## Dashboard Features

- **Campaign Performance:** Compare campaign activity, budgets, and outcomes.
- **Marketing Funnel Analysis:** Track impressions, clicks, engagement, and purchases.
- **Audience Segmentation:** Explore performance by gender, age group, country, and interests.
- **Ad Type Analysis:** Compare advertising formats and identify stronger-performing segments.
- **KPI Monitoring:** Review key advertising metrics through interactive visuals.
- **Budget Analysis:** Examine campaign budgets alongside advertising performance.

## Dashboard Preview

Add your dashboard screenshots below. Upload the images to a folder such as `images/` in this repository and update the filenames if needed.

```markdown
![Meta Ads Dashboard](images/dashboard.png)

![Campaign Performance Analysis](images/campaign-performance.png)
```

## Repository Structure

```text
Social-Media-Ad-Performance/
├── PowerBi/
│   └── SocialMediaAdPerformance.pbit
├── SQL/
│   └── SQLQuery1.sql
├── ad_events.csv
├── ads.csv
├── campaigns.csv
├── users.csv
└── README.md
```

*The structure above reflects the documented project files; adjust the paths if your repository uses a different layout.*

## Getting Started

### Prerequisites

- Power BI Desktop
- SQL Server or another compatible relational database
- The four required CSV data files

### 1. Clone the Repository

```bash
git clone [https://github.com/utkrashtsrepo/Meta-Ad-Performance-Dashboard]
cd Social-Media-Ad-Performance
```

### 2. Prepare the Data

Ensure that `ad_events.csv`, `ads.csv`, `campaigns.csv`, and `users.csv` are available in the locations expected by the Power BI template and SQL scripts.

### 3. Open the Power BI Template

Open `PowerBi/SocialMediaAdPerformance.pbit` in Power BI Desktop.

Configure the data source paths if prompted, then refresh the data to load the CSV files.

### 4. Run the SQL Queries

Connect to your database and execute the SQL scripts in the `SQL/` directory to explore advertising data and calculate performance metrics.

Update database connections and table names as required by your environment.

### 5. Explore the Dashboard

Use the dashboard filters and visualizations to compare campaign performance, analyze audience segments, and investigate advertising funnel metrics.

## Key Learnings

- Writing SQL queries to analyze advertising event data.
- Creating calculated KPIs and measures using DAX.
- Building interactive Power BI dashboards.
- Analyzing marketing funnel performance and audience segments.
- Translating raw advertising data into meaningful business insights.

## Conclusion

The Meta Ad Performance Dashboard demonstrates an end-to-end business intelligence workflow, combining SQL-based data analysis, DAX calculations, and Power BI visualizations to evaluate advertising performance. It provides a structured view of campaign activity, audience engagement, budget allocation, and purchase outcomes to support data-informed marketing decisions.

## Author

**Utkrasht Gupta**

- GitHub: [utkrashtsrepo](https://github.com/utkrashtsrepo)
