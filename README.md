# Shopping Dashboard: Full Insights

## Overview
This Power BI dashboard was developed as part of the DataMas series to showcase my expertise in data visualization and analytical insights. The dashboard provides a comprehensive overview of customer and sales data for a fictional shopping platform. It is designed with recruiters and Fortune 50 companies in mind, focusing on the clarity and usability of the insights presented.

## Features
### Key Performance Indicators (KPIs)
- **Total Revenue**: $233,080
- **Total Customers**: 3,900
- **Average Review Rating**: 3.75/5

### Visualizations
1. **Revenue by Category (Bar Chart)**: Visualizes revenue contributions across product categories.
2. **Revenue by Sex and Location (Stacked Bar Chart)**: Highlights demographic and geographic purchasing behaviors.
3. **Usage of Promo Codes (Pie Chart)**: Analyzes promotional code effectiveness.
4. **Shipping Performance by Customers (Stacked Bar Chart)**: Evaluates on-time and late delivery metrics across shipping methods.
5. **Purchase Tiers (Donut Chart)**: Categorizes customers into high, medium, and low purchase tiers.
6. **Monthly Revenue Trends (Line Chart)**: Tracks revenue growth over time.
7. **Customer Insights Table**: Displays customer-level details including demographics, preferences, and purchase behaviors.
8. **Sales Insights Table**: Breaks down sales data by product categories, payment methods, and shipping performance.

### Navigation
The dashboard features navigation buttons for seamless transitions between:
- **Home**: Overview of key metrics.
- **Customer Insights**: Focused details about customer demographics and behaviors.
- **Sales Insights**: Detailed breakdown of sales performance.

## Use Cases
- **For Recruiters**: Demonstrates skills in Power BI, data analytics, and storytelling with data.
- **For Businesses**: Offers actionable insights for improving sales and customer satisfaction.

## Technical Details
- **Tools**: Power BI Desktop
- **Data**: Synthesized customer and sales data, enriched with additional fields (e.g., Purchase Date, Shipping Performance, Age Group, Purchase Tier).
- **DAX Calculations**: 
  - **Shipping Performances**: `IF([Review Rating] >= 4, "On-Time", IF([Review Rating] >= 2, "Late", "Failed"))`
  - **Age Group**: `IF([Age] <= 30, "20-30", IF([Age] <= 40, "30-40", "40+"))`
  - **Purchase Tier**: `IF([Purchase Amount (USD)] >= 80, "High", IF([Purchase Amount (USD)] >= 50, "Medium", "Low"))`
  - **Purchase Date**: Based on seasonally realistic dates using DAX.

## Installation
1. Clone this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Explore the interactive features and filters.

## Contact
Feel free to connect with me on [LinkedIn](www.linkedin.com/in/saifansari1) or email me at saif.ansari9223@gmail.com for collaboration or feedback.
