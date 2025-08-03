# Power BI Sales Analytics Dashboard with Data Warehouse Optimization
This project showcases a Power BI dashboard and data model optimization based on a sample Data Warehouse. It covers advanced data modeling techniques, performance enhancements, and dynamic visualizations designed to deliver insightful sales analytics.
Project Overview
The goal of this project is to:
-	Analyze sales data from a structured Data Warehouse (based on AdventureWorks)
-	Optimize a Snowflake schema into a more efficient Star schema
-	Design an interactive Power BI report with dynamic measures and multiple date relationships

#### Key Features

##### Data Modeling Optimization
The original data model follows a Snowflake schema. For better performance and simplicity in Power BI, it was optimized into a Star schema by:
-	Flattening lookup dimensions
-	Reducing table joins
-	Keeping only relevant tables and relationships

##### KPI-Based Sales Dashboard
Some key performance indicators (KPIs) were created

##### Dynamic Measure Selection
A slicer allows users to switch between different measures (e.g., Sales, Quantity, Orders) dynamically, with both the measure values and chart titles updating accordingly.
