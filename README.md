Infosys Springboard Internship Project

🧾 Project Overview

This project is developed as part of the Infosys Springboard Internship under the theme Data Visualization Using Power BI. The objective is to demonstrate the ability to collect, transform, model, and visualize real-world data using Microsoft Power BI. The dashboard provides insightful, interactive visualizations to help stakeholders make informed, data-driven decisions.

🎯 Objective

To design and implement a fully interactive and visually appealing Sales Dashboard in Power BI that:

Analyzes key sales metrics

Tracks performance over time

Identifies trends and outliers

Supports decision-making through dynamic visualizations

📁 Dataset Details

Dataset Used: [Sample Superstore Dataset]
Source: Kaggle - Superstore Dataset

Tables Used:

Orders

Customers

Products

Regions

Returns (if applicable)

Number of Rows: 5000+
Data Fields:

Order Date

Product ID

Sales

Profit

Quantity

Customer Segment

Region, State, and City

🔧 Tools & Technologies Used
Tool	Description
Power BI	Data modeling, visualization
DAX	Calculated measures and KPIs
Power Query	Data cleaning and transformation
Excel (Optional)	Initial data exploration
📊 Dashboard Features

The dashboard includes the following visual elements:

🔹 Key KPIs

Total Sales

Total Profit

Total Quantity Sold

Profit Margin

🔹 Visualizations

Sales Trend Over Time – Line Chart

Top 10 Products by Sales – Bar Chart

Sales by Region/State – Map

Profit by Category/Sub-Category – Stacked Column Chart

Customer Segment Analysis – Donut Chart

Interactive Filters – Slicers for Date, Region, Category, etc.

🔹 Interactivity

Dynamic slicers for time, product category, and region

Drillthrough pages for deeper analysis

Tooltip customization for enhanced context

📈 DAX Measures Created
Total Sales = SUM(Orders[Sales])
Total Profit = SUM(Orders[Profit])
Total Quantity = SUM(Orders[Quantity])
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
Sales YTD = TOTALYTD([Total Sales], Orders[Order Date])

🚀 How to Use

Open Power BI Desktop

Load the provided .pbix file or import the dataset manually

Navigate through report pages using slicers and filters

Use the visuals to explore insights interactively

📚 Learnings

Data cleaning and modeling using Power Query Editor

Creating measures and KPIs using DAX

Designing professional dashboards using Power BI visuals

Enhancing user experience with interactivity and filters

Understanding business metrics in a sales environment

✅ Outcomes

This project showcases:

Real-world data handling and reporting skills

Ability to turn raw data into actionable business insights

Strong understanding of Power BI’s end-to-end workflow
