Sales Performance Dashboard – Power BI Project

Overview:
This project showcases a Sales Performance Dashboard built using Power BI, focusing on sales analysis, profit insights, and business growth trends.
It demonstrates end-to-end BI workflow — from data cleaning (Power Query) to data modeling (Power Pivot) and measure creation (DAX).

Tools & Technologies:
1.Power BI Desktop
2.Power Query – for data transformation
3.Power Pivot – for data modeling & relationships
4.DAX (Data Analysis Expressions) – for creating KPIs

Dataset
The dataset contains sales transactions with columns like:
OrderID, Date, Region, Product, Category, Sales, Quantity, Discount, Profit, and Customer Name.
It was created manually using realistic sales data patterns.

Project Workflow:
1.Data Cleaning (Power Query):
2.Removed duplicates & handled missing values
3.Converted data types (Date, Decimal, Text)
4.Added custom columns for Month & Year
5.Data Modeling (Power Pivot):
6.Created relationships between fact and dimension tables
7.Used a Star Schema design

DAX Measures:
Total Sales = SUM(Sales[Sales])
Total Profit = SUM(Sales[Profit])
Profit Margin = DIVIDE([Total Profit], [Total Sales])
Sales Growth % = DIVIDE([Total Sales] - [Sales LY], [Sales LY])


Visualizations:
1.KPIs: Total Sales, Profit, Quantity, Profit Margin
2.Charts: Sales by Region, Sales by Category, Monthly Sales Trend

Customer & Product performance analysis Dashboard Insights
1.Identified top-performing regions and products
2.Calculated sales growth and profit margins over time
3.Analyzed customer purchasing patterns
4.Built interactive visuals for better decision-making

<img width="1920" height="1080" alt="Sales1" src="https://github.com/user-attachments/assets/5e8c7813-700e-448c-98f2-74547b0e0ea1" />

<img width="1920" height="1080" alt="Sales2" src="https://github.com/user-attachments/assets/9fe47355-b1d0-4201-a011-63e2a5cf1add" />

<img width="1920" height="1080" alt="Sales3" src="https://github.com/user-attachments/assets/abe3c70b-ba39-4509-a412-c4cf8f0b06e2" />

<img width="1920" height="1080" alt="Sales4" src="https://github.com/user-attachments/assets/d0b854bc-8834-4c0d-92a1-7a4aea3fe31b" />

<img width="1920" height="1080" alt="Sales5" src="https://github.com/user-attachments/assets/4eabf3a7-05ce-4435-b266-6067766d5cd6" />

<img width="1920" height="1080" alt="Sales6" src="https://github.com/user-attachments/assets/2facfc58-085a-4568-b0fb-49f67355f071" />



