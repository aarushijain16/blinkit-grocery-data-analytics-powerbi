# blinkit-grocery-data-analytics-powerbi
This project presents an in-depth analysis of Blinkit's e-commerce transactional data through a comprehensive Power BI dashboard. It dissects revenue streams, evaluates product performance, and uncovers customer buying patterns to optimize sales, enhance product strategies, and improve overall business performance.

## Executive Summary:

This project conducts a comprehensive analysis of e-commerce transactional data from Blinkit, presented through an interactive Power BI dashboard. The analysis dissects revenue streams, evaluates product and outlet performance, and uncovers customer behavioral insights. The goal is to provide data-driven recommendations that optimize resource allocation, enhance product strategies, and inform targeted business decisions.

## Problem Statement:

The primary objective was to transform raw transactional data into actionable intelligence across key business areas:

- **Revenue Optimisation**: To precisely identify the most significant revenue contributors across item types, fat content, outlet types, and establishment years.

- **Marketing Effectiveness Enhancement**: To understand sales trends over time and across different outlet characteristics to guide strategic resource allocation and promotional efforts.

- **Customer Behavioural Insights**: To understand buying behavior patterns related to product attributes (e.g., fat content) and outlet characteristics, informing personalized marketing strategies and tailored product offerings.

## Data Sources and Engineering:

This project utilized a publicly available transactional dataset, BlinkIT Grocery Data.xlsx - BlinkIT Grocery Data.csv, obtained from Kaggle, which was then used to create the Power BI dashboard. The dashboard's visuals imply the dataset contains key columns such as:

- Item Fat Content

- Item Type

- Outlet Establishment Year

- Outlet Identifier

- Outlet Location Type

- Outlet Size

- Outlet Type

- Item Visibility

- Item Weight

- Sales

- Rating

My data engineering process (as implemented within Power BI or a preceding data preparation step) involved:

- **Data Acquisition**: Sourcing the publicly available transactional dataset from Kaggle.

- **Data Cleaning and Preprocessing**: Handled missing values, identified and removed duplicate entries, and ensured consistent data types for accurate analysis.

- **Feature Engineering**: Calculated key performance metrics and created new features to support deeper analysis, including:

  - Total Sales

  - Average Sales

  - Number of Items

  - Average Rating

## Methodology:

The analytical approach for this project was multi-faceted, focusing on turning raw data into actionable business intelligence through the Power BI dashboard:

- **Overall Performance Metrics**: Calculated and visualized key performance indicators such as Total Sales, Average Sales, Number of Items, and Average Rating.

- **Sales Trend Analysis**: Examined sales performance over different outlet establishment years to identify growth patterns and historical performance.

- **Product Performance Analysis**: Analyzed sales distribution by Item Type to identify top-selling categories and by Fat Content to understand customer preferences.

- **Outlet Performance Analysis**: Investigated sales performance across various Outlet Size, Outlet Location Type, and Outlet Type categories to identify high-performing channels and areas.

- **Fat Content by Outlet**: Analyzed the distribution of sales by fat content across different outlet tiers.

## Key Findings and Impact:

- **Overall Performance**: The dashboard shows a Total Sales of $1.20M, an Average Sales of $141, 8523 Number of Items, and an Average Rating of 3.9.

- **Fat Content Preference**: Regular fat content items generate significantly higher sales ($776.32K) compared to Low Fat items ($425.36K), accounting for approximately 65% of total sales.

- **Top Item Types**: Fruits and Vegetables ($0.18M) and Snack Foods ($0.18M) are the top-performing item types by sales, followed by Household ($0.14M) and Frozen Foods ($0.12M).

- **Sales by Outlet Establishment Year**: Sales show fluctuations, with peaks in 2012 ($132K), 2014 ($133K), 2016 ($131K), 2018 ($205K), 2020 ($129K), and 2022 ($131K). The year 2018 shows the highest total sales.

- **Outlet Size Impact**: Medium sized outlets contribute the most to sales, followed by Small and High (though "High" likely refers to "High" outlet size, not a location type).

- **Outlet Location Type Performance**: Tier 3 locations generate the highest sales ($472.13K), followed by Tier 2 ($393.15K) and Tier 1 ($336.40K).

- **Outlet Type Performance**: Supermarket Type1 is the dominant outlet type, generating $787.55K in sales, significantly more than Grocery Store ($151.94K), Supermarket Type2 ($131.48K), and Supermarket Type3 ($130.71K).

- **Fat Content by Outlet Tier**: Regular fat content consistently outperforms low fat across all tiers, with Tier 3 showing the highest sales for both.

## Strategic Recommendations:

- **Optimize Product Assortment based on Fat Content**:

  - Given the strong preference for Regular fat content items, ensure adequate stock and prominent placement for these products.

  - Investigate opportunities to market Low Fat alternatives more effectively or introduce new Low Fat products that align with customer tastes.

- **Focus on Top-Performing Item Types**:

  - Prioritize inventory management and promotional efforts for Fruits and Vegetables and Snack Foods to maximize sales from these categories.

  - Explore cross-selling and bundling opportunities with these popular items.

- **Leverage High-Performing Outlets and Locations**:

  - Analyze the success factors of Supermarket Type1 outlets and Tier 3 locations to replicate best practices across other outlets.

  - Consider strategic expansion or investment in Tier 3 locations.

- **Analyze Sales Trends for Seasonal/Event Planning**:

  - Further investigate the sales peaks and dips across establishment years to identify underlying seasonal trends or impact of specific marketing campaigns, informing future planning.

- **Tailor Strategies for Outlet Sizes**:

  - Develop distinct strategies for Medium, Small, and High sized outlets, optimizing product mix and promotions based on their sales performance and customer base.

## Tools and Technologies:

- **Data Visualization & Analysis**: Power BI

- **Data Source**: BlinkIT Grocery Data.xlsx - BlinkIT Grocery Data.csv from Kaggle

## Visualisations:

- Overall Sales Metrics (Total Sales, Avg Sales, No of Items, Avg Rating)

- Sales by Fat Content (Donut Chart)

- Sales by Item Type (Bar Chart)

- Sales by Outlet Establishment Year (Line Chart)

- Sales by Outlet Size (Bar Chart)

- Sales by Outlet Location Type (Bar Chart)

- Sales by Outlet Type (Table)

- Fat Content by Outlet (Stacked Bar Chart)
