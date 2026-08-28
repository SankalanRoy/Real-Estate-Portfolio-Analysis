Real Estate Sales & Revenue Optimization Analysis

Business Problem

A UK real estate agency faced challenges in identifying key drivers of revenue and optimizing sales strategies across its portfolio. Without a structured analysis of transaction history, property types, and market trends, the agency lacked visibility into which property categories yielded the highest returns, how property size impacted final pricing, and how discounting affected overall profit margins.

Executive Summary

This analysis evaluates real estate sales transactions, property demographics, and agent performance data for 2026 to identify primary revenue drivers and optimize pricing strategies. The dataset covers 22 property sales generating a cumulative £8.0M in total revenue.  Key findings reveal that while Apartments represent the highest volume of transactions (7 units), Houses generated the largest share of total revenue (£3.61M) due to higher unit pricing. The agency maintained tight control over pricing strategies, keeping overall discounting to ~0.12% of total potential revenue. Regression analysis confirms a strong positive correlation between property square footage and final selling price.

Methods Used

Data Cleaning & Preprocessing:Executed data filtering and handled numerical distributions using pandas and numpy in Python.  

Exploratory Data Analysis (EDA): Aggregated transaction data to determine monthly sales trends, property type distribution, and price variance.

Statistical Modeling & Visualization: Plotted price-per-square-foot dynamics and sales distributions using seaborn scatter plots and regression models (regplot).

Key Performance Indicators (KPIs) Uncovered

Total Revenue: £8,000,000  Total Properties Sold: 22 units  

Average Selling Price: £363,636.36  

Median Selling Price: £335,000.00  

Average Discount Given: £9,545.45 per property  

Overall Discount Ratio: ~0.12% of overall volume  

Top Revenue-Generating Segment: Houses (£3,610,000 total revenue)  

Highest Volume Segment: Apartments (7 units sold)

Key Recommendations

Pivot Marketing & Inventory Acquisition Toward Houses: While Apartments drive unit volume (7 sales), Houses contribute the highest total revenue (£3.61M). Prioritize listing acquisition and targeted marketing campaigns for detached/semi-detached houses to maximize top-line revenue growth.

Optimize Discounting Strategy for Slower-Moving Stock: With an overall discount ratio of just ~0.12% (£9,545.45 average discount per property), price negotiation margins are tight. Capitalize on this strong pricing power by maintaining firm listing prices on high-demand properties (Houses and Apartments), while using targeted 1–2% promotional pricing concessions strictly on lower-volume categories like Flats and Condos to accelerate sales velocity.

Implement Square-Footage-Based Dynamic Pricing: Regression analysis indicates a direct linear relationship between property size (area_sqft) and final sale price. Develop a standardized £/sqft pricing baseline across property types to help agents quote competitive listing prices, prevent underpricing large units, and shorten market turnaround time.

Capitalize on Seasonal Sales Peaks: Align marketing spend and agent promotional activity with the high-volume months identified in the 2026 sales breakdown to capture buyer demand when transaction velocity is naturally highest.
