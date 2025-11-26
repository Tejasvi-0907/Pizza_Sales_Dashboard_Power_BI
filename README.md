# Pizza Sales Analysis Dashboard - Power BI
## Project Overview
This project presents an interactive and insight-driven Power BI dashboard built using a pizza sales dataset. The objective was to analyze ordering patterns, revenue trends, and product performance to uncover actionable insights that can support business decision-making for a pizza store.

The dashboard offers a comprehensive view of sales behavior across different times of the day, days of the week, and pizza types. It is designed to help business managers quickly assess key performance indicators and respond effectively to customer preferences and operational needs.

## Dataset Overview
The analysis is based on a structured dataset consisting of the following key tables:

Orders – Contains order IDs, dates, and times of orders.

Order_Details – Includes order ID, pizza ID, and quantity.

Pizzas – Contains pizza ID, type, size, and price.

Pizza_Types – Includes pizza name, category, and ingredients.

These tables were connected using relationships based on order_id and pizza_id to build a relational data model in Power BI.

## Business Questions Answered
This dashboard was developed to answer critical business questions that a pizza store manager or owner would want to understand:

What time of the day do we receive the highest and lowest number of orders?

Which day of the week receives the most pizza orders?

What is the total revenue or sales generated?

Which pizza is ordered the most in terms of quantity?

Which pizza generates the highest sales revenue?

During which time of the day (morning, afternoon, evening, night) are most orders placed?

Which pizza category (e.g., Classic, Veggie, Supreme) is selling the most?

What is the total number of orders placed?

## Dashboard Features
Interactive Slicers – Allow users to filter the data by month or specific time periods

KPI Cards – Display Total Sales, Total Orders, and Top-Selling Pizza for a quick overview

Bar Charts – Used for comparing pizza popularity and revenue generation

Pie/Donut Charts – Display sales distribution by category

Line or Area Charts – Visualize ordering trends across different days

Column Charts – Show hourly sales volumes for time-based insights

Custom Time of Day Segmentation – Orders are categorized into Morning, Afternoon, Evening, and Night using DAX logic

Clean and Responsive Layout – Focuses on readability and decision support

## Tools and Techniques Used
Power BI Desktop

Data Modeling using relationships across multiple tables

DAX measures for calculating:

Total Sales

Total Orders

Sales by Hour

Top-Selling Pizza

Category-wise sales

Time-based transformations including:

Extraction of hour, weekday, and month

Categorization of time into defined periods (e.g., Morning, Evening)

## Key Insights and Business Value
Most orders occur during the evening, indicating peak demand during dinner hours

Weekends (Saturday and Sunday) show the highest ordering frequency

Certain pizzas, such as BBQ Chicken, are top performers in both quantity and revenue

Classic and Supreme categories are the most popular among customers

Low-demand hours and days can be targeted for promotions or operational adjustments

Inventory and staffing can be optimized based on peak and low-traffic periods

## Business Use Case
This dashboard provides actionable insights that can assist business managers in making informed decisions across several operational and strategic areas:

Optimize workforce scheduling during peak hours

Identify opportunities for promotional campaigns based on low-demand periods

Adjust inventory and procurement based on top-selling items

Track financial health and operational efficiency using KPIs

Improve marketing strategies by focusing on high-performing products and categories

Make data-backed menu and pricing decisions

## Conclusion
This is my first self-directed Power BI project, developed without any guided tutorials, and built entirely from scratch based on real-world business requirements. It demonstrates how a data analyst can use business intelligence tools to transform raw data into meaningful insights that drive operational and strategic improvements.

This project highlights the power of storytelling with data, and how visual analytics can contribute significantly to smarter and faster decision-making in a business environment.
