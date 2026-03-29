# Axia-Digital-Solutions-Marketing-Campaign-Performance
An end-to-end Power BI project showcasing marketing campaign performance analysis for Axia Digital Solutions, with interactive dashboards and data-driven insights


INTRODUCTION
This report presents the development of a Power BI dashboard that was made to monitor and analyse digital marketing campaigns across different channels, including Email, Instagram Ads, and Influencer Marketing. 
This dashboard provides insights into campaign performance, optimizes Ad spend, and improves decision-making.

DATASET OVERVIEW
The dataset includes:
•	Ad Spend
•	Impressions
•	Clicks
•	Conversions
•	Revenue
•	Campaign Dates (Year, Month)
•	Products
•	Marketing Channel
KPI’s(Key Performance Indicators)
The following KPI’s were created as card visuals:
•	Total Conversions
•	Overall ROI (Return on Investment)
•	Total Ad Spend
•	Total Clicks
•	Total Impressions
•	Total Revenue
CALCULATED DAX MEASURES
•	Click Through Rate(CTR): It shows the percentage of users who clicked on a link compared to the total number of viewers.
CTR(%)= Divide(SUM([Clicks]), SUM([Impressions]),0)*100
•	Return On Investment(ROI): It shows the percentage of how much was made and how much was spent.
ROI%=Divide[(SUM(Sheet1[Revenue(INR)])- SUM(Sheet1[Ad Spend(INR)]),SUM(Sheet1[Ad Spend(INR)]),0).
•	Conversion Rate:
The measure used for this:
Conversion Rate= Divide(SUM(Sheet1[Conversions]),SUM(Sheet1[Clicks])). 

VISUALS INCLUDED
•	Ad Spend by Channel(Clustered bar chart): Compares spend across channels.
•	Clicks VS Impressions(Donut Chart):Measures engagement.
•	Conversion rate by category(Clustered column chart): Shows product category efficiency.
•	Revenue by Product(Clustered column chart): Identifies top products.
•	ROI by products: Shows profits by the products.
•	ROI by category: Shows profits by category.
•	Time-based trends(Line Charts): Tracks conversions, clicks, spend, and ROI by month/year.
INTERACTIVITY
The dashboard includes slicers for:
•	Year
•	Month
•	Product Name
•	Category
•	Marketing Channel, to enable filtering across all visuals.

INSIGHTS PROVIDED
•	Top-performing products and categories.
•	Seasonal trends in campaign performance.
•	Ad Spend Efficiency
•	Engagement Patterns  

CONCLUSION
The dashboard helps Axia Digital Solutions see which campaigns work best, where money is well spent, and which areas need improvement. It gives clear insights that support smarter decisions and better marketing results.

