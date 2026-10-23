# Meta-Ad-Performance-Dashboard
Built a Meta Ads performance dashboard using SQL, Power BI, and DAX to analyze campaign budgets, impressions, clicks, engagement, and purchases. Developed KPIs for CTR, engagement, and conversion rates, with interactive visualizations to compare campaign performance and audience demographics and identify optimization opportunities.

Project Overview
This repository contains a Power BI Dashboard designed for the comprehensive analysis and optimization of Meta (Facebook & Instagram) advertising campaigns. It transforms raw ad event data, campaign budget information, and user demographics into actionable insights across the entire marketing funnel—from impression to final purchase.

The goal is to provide media buyers and marketing managers with the necessary tools to track performance, assess campaign efficiency, and refine audience targeting.

Objectives
Track ad performance metrics across multiple Meta platforms.

Understand engagement trends by gender, age, and country.

Identify top-performing ad types and campaigns.

Monitor click-through rate (CTR), engagement rate, and purchase rate.

Evaluate the impact of ad budgets on overall campaign success.

Key Metrics
Metric	Description
Impressions	Total number of ad views
Clicks	Number of times users clicked on ads
Shares	Number of ad shares
Comments	User comments received
Purchases	Conversion events after ad interaction
Engagements	Total interactions of Clicks, Shares , Comments.
CTR (Click Through Rate)	(Clicks ÷ Impressions) × 100
Engagement Rate	((Clicks + Shares + Comments) ÷ Impressions) × 100
Conversion Rate	Percentage of clicks that resulted in purchases.
Purchase Rate	(Purchases ÷ Impressions) × 100
Conversion Rate	Overall conversion from engagement to purchase
Total & Avg Budget	Campaign spend overview
🛠️ Tools & Technologies
Power BI Desktop – Data modeling, visualization, and dashboard creation

SQL Server – Data extraction and transformation

DAX – Calculated KPIs and advanced measures

Excel/CSV Files – Data source (ad_events, ads, campaigns)

Required Data Sources
The dashboard requires the following four CSV files to be loaded into Power BI. They represent a simplified but complete ad ecosystem:

File	Description
ad_events.csv	Contains all user interactions with ads
ads.csv	Details of each advertisement (platform, ad type, demographics)
campaigns.csv	Campaign-level data including budgets and status
users.csv	User demographic and interest data for segmentation.
Principal Visualizations
Dashboard

image image
How to Set Up and Run the Dashboard
Power Bi
Clone this repository
bash  git clone https://github.com/AmeeJoshi-MCA/Social-Media-Ad-Performance.git

Place Data Files: Ensure the four required .csv files (ad_events.csv, ads.csv, campaigns.csv, users.csv) are placed in the same folder as the .pbix file.

Open the file in Power BI Desktop.

Refresh Data: If the data doesn't load immediately, go to the Home tab and click Refresh to load the data from the CSV files. (The Power Query steps assume the CSV files are in the same directory as the PBIX file).

SQL
Connect to your database (MySQL, PostgreSQL, etc.).
Run the SQL scripts in the sql/ folder to extract raw data and all kpi queries.
🏁 Conclusion
The Meta Ad Performance Dashboard is more than just a data visualization project — it’s a complete analytical solution that showcases my ability to transform complex advertising data into clear, actionable insights.

Through this project, I demonstrated expertise in:

SQL for data extraction and transformation,

DAX for advanced KPI calculations,

Power BI for designing clean, interactive, and user-centric dashboards,

Strong understanding of digital marketing analytics and business intelligence storytelling.

This project reflects end-to-end data analytics workflow — from building robust SQL queries to creating executive-level dashboards that help marketing teams make data-driven decisions.
