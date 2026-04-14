# meta-ads-performance-analysis-
📊 Meta Ads Performance Analysis (Power BI Project)
A Power BI dashboard designed to analyze paid advertising performance across Facebook and Instagram campaigns. The report helps marketing teams evaluate reach, engagement, conversions, and budget utilization to optimize campaign ROI.

🎯 Business Objective
Compare performance between Facebook vs Instagram
Track ROI, conversions, and engagement
Optimize budget allocation
Understand audience behavior across demographics, geography, and time.

📌 Scope
✔ In Scope
Paid ads on Facebook and Instagram
✖ Out of Scope
Messenger, Audience Network
Organic engagement (paid ads only)

📐 KPIs & Definitions
Impressions = Count of event_type = Impression
Clicks = Count of event_type = Click
Shares = Count of event_type = Share
Comments = Count of event_type = Comment
Purchases = Count of event_type = Purchase
Engagements = Clicks + Shares + Comments
CTR = (Clicks ÷ Impressions) × 100
Engagement Rate = (Engagements ÷ Impressions) × 100
Conversion Rate = (Purchases ÷ Clicks) × 100
Purchase Rate = (Purchases ÷ Impressions) × 100
Total Budget = Sum(campaigns.total_budget)
Avg. Budget per Campaign = Total Budget ÷ Campaign Count

📊 Report Visuals
1️⃣ Target Gender – Donut Chart
Shows performance split by gender using a dynamic metric selector.
2️⃣ Target Age Group – Bar Chart
Displays engagement across age groups.
3️⃣ Country – Map
Shows geographic performance using bubble size or color intensity.
4️⃣ Calendar Month – Calendar Heat Map
Highlights seasonal trends and peak activity months.
5️⃣ Weekly Trend – Stacked Column (by Ad Type)
Compares weekly performance and ad type contribution.
6️⃣ Hourly Trend – Area Chart
Shows user activity patterns by hour of day.
7️⃣ Ad Type – Matrix
Compares metrics across ad types and platforms (Facebook vs Instagram).

## Tools Used
### 1. Power BI Desktop
Used to build the complete dashboard, visuals, and data model.
### 2. Power Query
Used for data cleaning, transformation, and preparing tables for reporting.
### 3. DAX (Data Analysis Expressions)
Used to create KPIs, calculated measures, and time‑based metrics.
### 4. Data Sources
- ads
- ad_events
- campaigns
- users
- Date table

Screenshot :-
Dashboard Preview :- (https://github.com/vinay70110/meta-ads-performance-analysis-/blob/main/Meta%20Ad%20Dashboard.png)
