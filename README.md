# Bike_Sales_Analysis_Project
Excel-based exploratory data analysis and visualization of bike purchase behavior.
This project analyzes a dataset of ~1,000 customers to uncover key factors influencing bike purchases. It includes data cleaning, feature engineering (age brackets), pivot tables, interactive slicers, and a comprehensive dashboard.
📊 Project Overview

Dataset: Customer demographics, income, education, occupation, commute distance, region, and bike purchase status.
Tools Used: Microsoft Excel (Pivot Tables, Slicers, Charts, Dashboard).
Goal: Identify customer segments most likely to purchase bikes and provide actionable business insights.

Key Features

Raw data processing in bike_buyers and worksheet (with added Age Bracket).
Interactive Pivot Tables with slicers for dynamic exploration.
Dashboard summarizing key metrics and trends.
Slicers for: Region, Age Bracket, Marital Status, Gender, etc.

📈 Key Findings
1. Overall Purchase Rate

Total Customers: 1,026
Purchased Bike: 495 (≈48%)
Did Not Purchase: 531

2. Demographics & Purchase Behavior

Income: Buyers have slightly higher average income ($57.5K vs $55K for non-buyers).
Age:
Middle-aged customers (core buyers) show strong purchase rates.
Adolescents and older customers have lower conversion in some segments.

Gender & Marital Status: Variations exist; detailed breakdowns available via dashboard slicers.
Region:
North America has the largest sample.
Europe and the Pacific show distinct patterns.

3. Commute Distance Impact (Strongest Predictor)
Commute Distance No  Yes  Total  Purchase(%)
0-1 Miles       171 207   378    55%
2-5 Miles        67  95   162    59%
1-2 Miles        93  83   176    47%
5-10 Miles      120  77   197    39%
10+ Miles        80  33   113    29%

Insight: Customers with shorter commutes (0-5 miles) are significantly more likely to buy bikes.

4. Other Insights from Pivots
Occupation (e.g., Professional, Management) and Education level correlate with higher income and purchase propensity.
Home ownership and the number of cars provide additional segmentation signals.

🖼️ Dashboard Highlights
The Dashboard sheet provides at-a-glance visuals:

Overall purchase rate KPIs.
Charts by Region, Age Bracket, Commute Distance, and Income bands.
Interactive slicers for filtering (try Region + Age + Commute combinations).
Pivot-driven insights on average income by purchase status.

🔍 How to Use

Open the Excel file.
Go to the Dashboard sheet.
Use the Slicers to filter dynamically.
Explore the Pivot Table sheet for deeper cross-tabs.
Review raw data and derived columns in the worksheet.

💡 Recommendations

Target Short Commute Customers: Focus marketing on urban/suburban areas with commutes under 5 miles.
Middle-Aged Professionals: High-potential segment — tailor campaigns around income and lifestyle.
Regional Strategies: Customize offers by region (e.g., higher income incentives in certain areas).
Upsell Opportunities: Bundle bikes with accessories for higher-income or multi-car households.
Further Analysis: Consider adding predictive modeling (e.g., in Python/R) using features like Income, Commute, Age, and Occupation.
