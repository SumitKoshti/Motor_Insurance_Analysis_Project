# Motor_Insurance_Analysis_Project
🎯 Project Objective : Between 2014 and 2018, EIC was a prominent player in the motor insurance industry. However, due to consistent underwriting losses, the company ceased operations in 2019.
To understand the root causes of these losses, an in-depth analysis is required to uncover key trends, risk patterns, and operational inefficiencies that may have contributed to the financial downfall.
The objective is to identify actionable insights that could have potentially prevented the losses and provide strategic recommendations for future players in the motor insurance domain to avoid similar pitfalls.

See the report -- >>
![Power BI Report](Report.jpg)

Check full dashboard -->>
[Power BI Dashboard!](https://app.powerbi.com/view?r=eyJrIjoiOWJhYTlmNGItYWU2Zi00YTkzLTgwOTItNTQ0YzMxODlhMWRiIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)


🔧 Project Process Summary -->>
This end-to-end analytics project leveraged ☁️ Azure, ❄️ Snowflake, 📊 Power BI, and 🐙 GitHub to analyze motor insurance data and uncover key business insights.

☁️ Data Storage in Azure
1. Created Resource Group, Storage Account, and Blob Container
2. Uploaded raw datasets into Azure Blob Storage

❄️ Data Ingestion via Snowflake
1. Configured Storage Integration between Azure and Snowflake
2. Defined File Format, created External Stage, and structured Table Schema
3. Loaded data using COPY INTO from Azure Blob to Snowflake

🧹 Data Cleaning
1. Cleaned data using SQL in Snowflake:
2. Removed duplicates, filled nulls, standardized formats
3. Prepared a clean, analysis-ready dataset

📊 Analysis & Visualization in Power BI
1. Connected cleaned Snowflake data to Power BI Desktop
2. Built Data Model and created KPIs using DAX Measures
3. Designed interactive dashboards and visual reports
4. Published final report to Power BI Service for stakeholder access

🐙 Version Control with GitHub
1. Uploaded all project assets: SQL scripts, .pbix file, and documentation
2. Enabled version control and easy collaboration via GitHub


📊 Key Insights from the Analysis -->>

📉 Severe Financial Loss (2014–2018)
1. Total Policies Opened: 509,000
2. Total Premium Collected: $4 Billion
3. Total Claim Paid: $9 Billion
4. ➤ Indicates a massive underwriting loss, with claims more than 2x the premium earned.

🚗 Policy Type Performance
1. Top Policy Buyers: Motorcycle, Truck, Pickup, Automobile, Bus
2. Only Motorcycles were Profitable
3. ➤ All others, especially Truck, Pickup, Bus, led to losses due to claims exceeding premiums.

📦 Claim Category Trends
1. Top Claim Categories in 2015:
General Cartage: $1.43B
Own Goods: $541M
Fare Paying Passengers: $349M
➤ Post-2015, claim payouts declined, indicating better control or reduced exposure.

📊 2018 Showed Slight Improvement
1. Premium Collected: $384M
2. Claims Paid: $337M
3. Claims-to-Premium Ratio: 114%
4. ➤ Some positive values, losses reduced, suggesting operational improvement.

🧍 Claim Behavior by Gender Category
. Gender Code ‘0’ accounted for over 63% of total claims
➤ This demographic may represent a higher risk profile and needs further segmentation.

🚙 Top Claiming Vehicle Manufacturers
. Toyota, Isuzu, and Nissan were the top 3 brands with the highest claim volume
➤ May reflect brand popularity, usage in high-risk segments, or vehicle durability factors.


