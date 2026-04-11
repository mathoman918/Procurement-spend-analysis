# Procurement Spend Analysis

## Project Overview
This project analyzes procurement spending data to identify spending patterns, supplier performance, and cost optimization opportunities. The goal is to transform raw procurement data into meaningful insights that support better decision-making in supply chain and procurement management.

## Objectives
- Calculate total procurement spend  
- Identify top suppliers by spend  
- Analyze spending by category  
- Track monthly procurement trends  
- Identify top buyers  
- Analyze most purchased items  
- Identify cost-saving opportunities  


## Dataset Description
The dataset contains procurement transaction records with the following fields:

| Column | Description |
|-------|-------------|
| TransactionID | Unique transaction identifier |
| ItemName | Name of purchased item |
| Category | Item category |
| Quantity | Quantity purchased |
| UnitPrice | Price per unit |
| TotalCost | Total transaction cost |
| PurchaseDate | Date of purchase |
| Supplier | Supplier name |
| Buyer | Buyer/department |


## Data Cleaning
The dataset was cleaned and prepared before analysis:
- Removed duplicate records  
- Checked and handled missing values  
- Converted data types (dates, numeric fields)  
- Verified TotalCost = Quantity × UnitPrice  
- Created Month and Year columns  
- Standardized supplier and category names  

## Data Processing & Analysis
SQL was used to transform and analyze the data:
- Total procurement spend calculation  
- Spend by supplier and category  
- Monthly spend trend analysis  
- Buyer spending analysis  
- Most purchased items analysis  
- Average unit price per category  
- Supplier transaction count  

## Visualizations & Dashboard
The analysis was visualized using Excel and Power BI:

- Total Spend (KPI)  
- Spend by Supplier (Bar Chart)  
- Spend by Category (Pie Chart)  
- Monthly Spend Trend (Line Chart)  
- Spend by Buyer (Bar Chart)  
- Most Purchased Items (Bar Chart)  
- Average Unit Price per Category  
- Supplier Transaction Count  

Interactive filters (slicers) were used for:
- Category  
- Supplier  
- Buyer  

## Key Insights
- The highest procurement spend was observed in high-value categories such as ______  
- A small number of suppliers contributed to the majority of total spend  
- Monthly spending trends showed peaks in ______  
- Certain buyers were responsible for a significant portion of total spend  
- Frequently purchased items had low unit cost but high volume  

## Recommendations
- Negotiate pricing with top suppliers to reduce costs  
- Diversify suppliers to reduce dependency risk  
- Monitor high unit price categories for cost control  
- Implement monthly spend tracking dashboards  
- Optimize purchasing strategies based on demand patterns  

## Tools Used
- SQL (Databricks)  
- Microsoft Excel
- Microsoft PowerPoint 
- Power BI  
- GitHub  
