# Marketing Campaign Analysis: Power BI Dashboard

## Project Objective
The primary objective of this project is to build an interactive Power BI dashboard that visualizes campaign data to effectively compare performance across different segments. The dashboard is strategically designed to highlight critical business insights—specifically ROI, total revenue, and overall spending—to enable data-driven decision-making for future marketing budget allocations.

## Dataset Used
- <a href = "https://github.com/venkatakrishnanbalaji/Marketing_Campaign_Analysis/blob/main/marketing%20campaign%20performance.csv"> Marketing Campaign Performance </a>
- <a href = "https://github.com/venkatakrishnanbalaji/Marketing_Campaign_Analysis/blob/main/marketing%20campaign%20details.csv"> Marketing Campaign Details </a>
- <a href = "https://github.com/venkatakrishnanbalaji/Marketing_Campaign_Analysis/blob/main/region%20performance.csv"> Region Performance </a>

## Questions (KPIs) and Charts
The dashboard was built to answer key business questions using the following specific metrics and visualizations:
- Key Performance Indicators (KPI Cards): What are the top-level results for Total Revenue, Total Spend, Average ROI, and the single Best Campaign?
- Stacked Column Chart: How do Total Spend and Total Revenue compare across different Regions?
- Combo Chart: What is the relationship between Total Spend (volume) and Average ROI (efficiency) by Campaign Name?
- Bar Chart: How do the various campaigns rank based on their Total ROI?
- Pie Chart: What is the breakdown of the number of campaigns by Campaign Type (Digital vs. Traditional)?
- Gauge Chart: How does the cumulative Total ROI track alongside the Average ROI?

- Dashboard Interaction <a href = "https://github.com/venkatakrishnanbalaji/Marketing_Campaign_Analysis/blob/main/Marketing_campaign_analysis_reportpage.png"> View Dashboard </a>

## Process
The project was executed through a structured, four-task workflow:
- Task 1: Data Preparation: Imported 3 distinct CSV files into Power BI. The dataset was cleaned by handling nulls and duplicates, correcting data types, and renaming columns for clarity (e.g., standardizing headers to "Campaign_Type" and "Total_Spend").
- Task 2: Data Modeling: Established a robust data model using One-to-Many relationships. The Marketing_Campaign_Performance fact table was connected to the Marketing_Campaign_Details table via "Campaign Name", and connected to the Region_Performance table via "Region".
- Task 3: DAX Measures: Created targeted analytical measures within the performance table, including Total Impressions, Total Clicks, Total Conversions, Total Revenue, Total Spend, Total ROI, Average ROI, and a dynamic measure to identify the Best Campaign.
- Task 4: Visualizations: Designed a professional, high-contrast dashboard incorporating all required charts and interactive slicers to allow stakeholders to filter by specific Regions and Industries.

## Dashboard
<img width="1163" height="656" alt="Marketing_campaign_analysis_reportpage" src="https://github.com/user-attachments/assets/00dbc0da-a6e4-4be5-8100-bb5783ce1528" />

## Project Insights
Based on the final dashboard data, several key insights were identified:
- Overall Financials: The marketing portfolio generated an impressive Total Revenue of 42.54M from a Total Spend of 25.69M, resulting in a baseline Average ROI of 0.68.
- The Top Performer: "Influencer Marketing" is officially the Best Campaign, driving the highest Total ROI (137.35) and peaking with an Average ROI of 1.0.
- Budget Inefficiencies: The highest volume of Total Spend is allocated to "Search Engine Ads", yet this channel only yields a mediocre Average ROI. Conversely, "TV Commercials" is the lowest performing campaign overall, dragging down efficiency with a Total ROI of just 50.62.
- Geographic Strengths: Africa ($8.6M) and North America ($7.5M) currently stand as the strongest markets, leading the portfolio in Total Revenue.
- Platform Mix: The current campaign strategy leans favorably toward Digital platforms, which make up 62.5% of the active campaign types compared to 37.5% Traditional.

## Final Conclusions
The data reveals a clear misalignment between budget allocation and campaign efficiency. While the overall revenue is strong, the Average ROI of 0.68 is being actively suppressed by overspending on underperforming channels like TV Commercials and high-cost Search Engine Ads. To optimize future marketing efforts, the organization should freeze or reduce spend on low-yield traditional media and immediately reallocate those funds to scale Influencer Marketing. Piloting these increased Influencer budgets in top-grossing regions like Africa and North America will likely yield the fastest increase in overall Total Revenue.   

