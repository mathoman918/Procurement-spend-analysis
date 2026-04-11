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
| Buyer | Buyer Name |


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

- Total Spend  
- Spend by Supplier 
- Spend by Category
- Monthly Spend Trend
- Spend by Buyer
- Most Purchased Items
- Average Unit Price per Category
- Supplier Transaction Count

Interactive filters (slicers) were used for:
- Category  
- Supplier  
- Buyer  

## Key Insights
- Office Supplies account for the largest share of procurement spend (~56%), indicating a major operational cost driver.
- TechMart Inc. is the highest spending supplier (~336K), followed by QuickDeliver Ltd., showing strong supplier dependency.
- Procurement spend is concentrated among a few suppliers, which introduces supply risk.
- Monthly spend trends show fluctuations, suggesting seasonal or demand-driven purchasing patterns.
- High-frequency items contribute to operational efficiency but have lower cost impact.
- Some categories have high unit prices, indicating opportunities for cost negotiation.  

## Recommendations
- Establish supplier negotiation strategies for top vendors
- Diversify supplier base to reduce dependency risk
- Monitor high-cost categories and implement cost controls
- Introduce procurement budgeting and forecasting
- Use dashboards for continuous spend monitoring 

## Tools Used
- SQL (Databricks)  
- Microsoft Excel
- Microsoft PowerPoint 
- Power BI  
- GitHub  
