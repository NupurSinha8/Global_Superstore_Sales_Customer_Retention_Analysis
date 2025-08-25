Global Superstore Sales & Customers Retention Insight Dashboard

Objective - To analyze sales and customer data from the Global Superstore dataset and build an interactive Power BI dashboard that provides key insights into: 
Sales performance, Customer retention and acquisition, Profitability trends, Regional and category-level insights

Tools & Technologies Used - Power BI - Dashboard creation, Dax measures, visualizations
SQL & Excel for Data cleaning, and preparation
Power Query for Data Transformation

The dataset was modeled into a Star Schema to support efficient reporting and analytics in Power BI.
FactSales is the central transaction table.
Dimension Tables (Customer, Product, Date) provide descriptive attributes for slicing and dicing. Enables calculations such as: YOY Sales Growth, Customer Retention, Segment-wise Profit

Dashboard Insights
Total Sales: $0.50M with YOY decline of –6%  
Customer Retention: ~95%, showing a strong base of repeat customers  
Average Order Value: ~$505 per transaction  
Top States: England, California, New York drive maximum sales  
Profitability: Technology is the most profitable category, while some sub-categories (e.g., Tables) incur losses  
Returning vs New Customers: Majority are returning customers, highlighting loyalty but limited new acquisition  
Region-wise Trends: North and West regions lead in sales

Challenges Faced
Handled negative YOY growth values (initially showed as 0, fixed with correct DAX formula)  
Created customer retention measure with distinct count logic across years  
Formatting metrics to percentage vs decimal values (e.g., 0.95 → 95%)  
Structuring KPIs vs visuals (Card vs KPI visuals in Power BI)

Learnings
Implemented DAX time intelligence functions for YOY comparison  
Calculated customer retention & acquisition from transactional data
Created KPIs Total Sales, YOY Sales Growth %, Total Profit, Customer Retention Rate, Average Order Value
Difference between Card visual vs KPI visual in Power BI  
Designed business-ready dashboards with storytelling approach

<img width="894" height="504" alt="image" src="https://github.com/user-attachments/assets/66d692f5-261f-4e92-944f-334961cce5ff" />

