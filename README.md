# LITA_Class_Documentation
# Sales and Trade Performance
## Table of Contents
 ### Project Overview
 ### Objectives 
 ### Data Source 
 ### Tool
 ### Data Cleaning and Preparation
 ### Exploratory Data Analysis
 ### Data Analysis And Visualization 
 ### Dashboard 
 ### Conclusion


# Project Overview
In today's competitive business landscape, data-driven decision-making is crucial for sustaining growth. This project leverages real-world sales data to uncover patterns, trends, and actionable insights. The dataset covers multiple transactions across regions, stores, and markets within Nigeria, focusing on different business models, product lines, and performance metrics. The goal is to analyze key factors affecting sales performance, highlight regional variations, and recommend strategies to optimize business operations.
The results from this project will provide valuable insights into customer behavior, product performance, and market segmentation, which can help management make informed decisions to maximize revenue and improve operational efficiency.This project involves the analysis of sales data from various regions and markets, focusing on the performance of different product lines and business models. The dataset contains records of transactions across multiple stores within Nigeria’s Federal Capital Territory, offering insights into product performance, revenue generation, and customer behavior.

# Objectives
The goal of this project is to conduct a comprehensive analysis of the dataset to uncover trends, identify challenges, and provide actionable recommendations for business growth. Below are the key objectives:
- Regional and Market Performance: Analyse the region and markets that generate the highest and lowest revenue, the underperforming regions that need attention

- Product Line Performance: Determine the product categories (e.g., service plans, parts) that generate the most revenue and units sold, the certain products that are more popular in specific markets or regions

- Customer Purchase Behavior:Identify different transaction categories (low, medium, high) impact revenue, customers purchasing higher quantities on specific days (e.g., weekends vs. workdays)

- Temporal Analysis: Identify how sales trends vary across fiscal periods, the seasonal patterns that impact revenue generation or sales volume

- Data Quality Issues and Improvements: Clean and manage missing or redundant data to improve the quality of insights, Generate new features if necessary (e.g., average revenue per transaction).

# Data source
The primary source of used is Data sales.CVS which was obtained from The Incubator Hub

# Tool
-Microsoft excel {Download here(https://microsoft-excel.en)}
1. For Data Cleaning
2. For Analysis
3. For Data Visiualiation
   
-GitHub for Portfolio Building

 Methodology
The analysis will follow these steps:

# Data Cleaning and preparations 
The following actions were performed:
1. Data Loading, Inspection ,organization, and exploration using pivot tables
2. Handle missing values and remove unnecessary columns
3. Data cleaning and formatting
4. Standardize dates and fiscal periods for time-based analysis 
5. Preliminary analysis to summarize key trends and metrics
6. Descriptive Analysis Using Pivot Tables

# Exploratory Data Analysis
The purpose of this EDA is to gain a preliminary understanding of the dataset through statistical summaries and visualizations. This step ensures data quality, helps identify trends, and provides a foundation for more advanced analysis.
- What is the aggregate revenue and units sold by region, market, and line of business.
- Compare performance across different transaction categories.
- Visualize trends over time to identify seasonality or fluctuations across fiscal periods.
- Segment markets by performance and categorize transactions to reveal behavioral trends.

# Data Analysis and  Data Visualization
This section covers key findings and actionable insights across regions, product lines, and sales trends. Using aggregated metrics, comparative analysis, and visualizations, the objective is to provide a business narrative based on data.

### Regional Performance Analysis
The dataset captures sales across multiple regions, allowing us to identify top-performing areas and markets.


### Revenue by Region:This chart shows revenue distribution across different geographical regions.
The South West and North East regions seem to generate the most revenue, while North Central has the lowest performance.South West is a high-performing region both in terms of revenue and units sold. Focusing on expanding in this area could maximize returns.Focus on high-performing regions (South West & North East) by increasing marketing campaigns, product offerings, and service availability. Investigate reasons for low performance in North Central (e.g., market conditions or operational challenges) and develop region-specific strategies (like promotions or partnerships). Explore potential for expansion in the South South and South East regions, given their moderate performance.

![Revenue by region](https://github.com/user-attachments/assets/b5a6219a-dcaf-4b73-8291-691f91a4dfa8)


### Revenue by Model: 
This visualization categorizes revenue based on product models (or business lines).
One model outperforms the others significantly, indicating a potential key driver for the business. The team should prioritize the top-performing model by ensuring continuous supply and investing in targeted promotions. Analysis of underperforming models to identify improvement areas (e.g., redesign, better features, or discounts).
and Considering phasing out low-performing models or bundling them with popular ones to drive additional revenue.

![Revenue By Model](https://github.com/user-attachments/assets/aed52934-8b7e-4b66-a75a-16de5cae6c83)

### Revenue by Copier Sales:
The pie chart breaks down total revenue (73.03bn) into different business categories:
Copier Sales: 51.87bn
Parts: 7.54bn
Printer Sales: 6.06bn
Copier Sales represent the majority of revenue, suggesting that this line of business is the primary source of income. THis can  be improved by Maintaining or expand the copier product line, given its strong contribution, Introducing premium copier models or extended service plans to increase revenue further and Monitoring the performance of parts and printer sales closely and explore cross-selling opportunities with copier products.

![Revenue by copier sales](https://github.com/user-attachments/assets/95d6e5af-dca2-4048-bd90-405c7b05f612)

### Region by Unit Sold :
This chart displays the number of units sold across regions. South West recorded the highest unit sales, followed by South South and South East. This insight suggests that these regions have higher demand for products.Increase product availability and promotions in high-performing regions to further boost unit sales, Identify factors driving sales in South West and replicate them across other regions, In underperforming regions (like North Central), The team should conduct customer surveys to understand demand patterns and preferences.

![Region by unit sold](https://github.com/user-attachments/assets/c56e3e1c-589d-4f58-a56c-0d3570fd9325)


### Day Category by Unit Sold :
Most units were sold on workdays, while sales on holidays, public observances, and seasonal days are minimal. This trend emphasizes that regular business days are crucial for achieving high sales performance. The team should introduce special discounts or flash sales during public holidays and observances to stimulate demand during low-sales periods, Analyze customer behavior patterns to understand why sales peak on workdays, and develop targeted campaigns to extend these sales trends to weekends and holidays.

![Day Category by Unit sold](https://github.com/user-attachments/assets/e500cbca-550e-410c-b984-8fde78f03f43)


### Trade Date by Revenue:
The line chart tracks revenue growth across specific periods. It shows a steady rise in revenue from March 2014 to Q1 2015, indicating positive growth over time.
Maintain the growth momentum by identifying and reinforcing the drivers of revenue during this period (e.g., seasonal demand, marketing strategies), Develop a quarterly sales forecast and ensure adequate resources are available to meet projected demand and Analyze any dips or stagnation to prevent similar patterns in future periods.

![Trade date by revenue](https://github.com/user-attachments/assets/a7f638f5-af09-4674-beca-b3321b65532f)


### Top 5 Markets by Revenue:
The bar chart highlights the highest-performing markets:
Ekiti
Abia
Bayelsa
Akwa Ibom
Kogi
These states contribute significantly to total revenue, making them key focus areas.
Double down on marketing and operations in these top markets to further boost revenue, Analyze the factors driving success in these states and explore replicating them in other areas and identify any seasonal trends within these markets to time product launches and promotional campaigns effectively.

![Top 5 Market](https://github.com/user-attachments/assets/5100ffc5-986e-4e66-b835-1f0457de1a3f)


### Trade Date by Unit Sold:
This donut chart compares the total units sold in 2014 and 2015:
2014: 517,013 units
2015: 269,665 units
The drop in sales volume between the two years could indicate either market shifts or changes in strategy. Investigate the reason for the significant decline in sales from 2014 to 2015 (e.g., market changes, supply chain issues, or new competitors).Consider introducing new products or promotional campaigns to recover from the decline and evaluate customer satisfaction and market dynamics during this period to pinpoint challenges.

![Revenue by copier sales](https://github.com/user-attachments/assets/ab805d83-163c-46d6-8630-6b02a6b73620)


### Line of Business by Unit Sold:
This pie chart categorizes units sold by different business lines:
Copier Sales: 493,826 units
Printer Sales: 257,766 units
Service Plans: 22,291 units
Copier products dominate unit sales, aligning with the revenue distribution chart. the company should continue investing in copier products, as they dominate unit sales. Explore ways to boost sales for printers and service plans, such as bundling services with copiers or offering loyalty programs, Introduce training programs for sales teams to improve their effectiveness in selling underperforming business lines.

![Line of Business by unit sold](https://github.com/user-attachments/assets/3068b5bc-1c56-432a-9cba-606fa0a591f0)

# DASHBOARD
![Sales report Dash board](https://github.com/user-attachments/assets/e3d8fd2c-43bb-4d66-831d-c2a9a4d5e4db)


# FINDINGS AND INSIGHTS
Total Revenue stands at 73.03bn, indicating strong overall business performance.
Average Revenue per transaction is 2,371,246, showing that each sale generates significant income.
A total of 786,678 units were sold over the entire period, with 269,665 units sold in 2015 alone.
The highest recorded revenue from a single source is 5.57bn, indicating peak performance in a specific area, likely from a high-value product or market.

2. Regional Performance
South West and North East regions lead in revenue generation, while North Central shows the lowest revenue contribution.
The South West region also recorded the highest unit sales, followed by the South South and South East regions.

Recommendation: Prioritize high-performing regions by increasing product availability and marketing efforts while investigating the poor performance of the North Central region.

3. Product Performance by Model and Business Line
One product model outperforms the others in terms of revenue.
Copier products dominate both revenue and unit sales, with 51.87bn in revenue and 493,826 units sold. This shows that copier products are the business’s main revenue driver.
Parts and printer sales contribute moderately to overall revenue but lag behind copier sales. Service plans have the lowest contribution.

Recommendation:Invest more in copier products and explore cross-selling parts and service plans with copiers to increase their uptake.

4. Market Analysis
The top 5 markets by revenue are:
Ekiti
Abia
Bayelsa
Akwa Ibom
Kogi
These markets show significant revenue contributions and are critical to business growth.

Recommendation:Reinforce marketing efforts and operations in these top markets and analyze their success factors for replication in other regions.

### Key Insights:
Copier products are both the top revenue generator and the most frequently sold product, confirming their central role in business success.
The South West region and Ekiti market are crucial for revenue and unit sales, highlighting key areas for future growth and focus.
Unit sales have declined from 2014 to 2015, warranting further investigation to prevent further drops.
The business is highly dependent on workday sales, which could present an opportunity to explore new sales strategies for weekends and holidays.

# Conclusion
The analysis of the sales report reveals key areas of strength, opportunities for improvement, and actionable insights for sustained business growth. The company's overall performance is strong, with 73.03bn in total revenue and 786,678 units sold, driven primarily by copier products, which dominate both revenue and unit sales.

The South West region emerges as a major contributor, performing exceptionally in both revenue and units sold, making it a strategic area for continued investment. Similarly, the **top markets—Ekiti, Abia, Bayelsa, Akwa Ibom, and Kogi—**play pivotal roles in revenue generation, underscoring the importance of market-specific strategies. However, the underperformance in North Central requires further attention to unlock its potential.

A concerning trend is the decline in unit sales between 2014 and 2015, which signals the need for a deeper investigation into market dynamics and the company’s sales strategy. Additionally, the business’s heavy reliance on workday sales presents an opportunity to develop promotional campaigns targeted at holidays and weekends to drive additional revenue.

Moving forward, the business should prioritize high-performing products and regions, boost sales of underperforming items like service plans, and explore new strategies to increase non-workday sales. Addressing the sales decline and unlocking underperforming markets will also be essential for achieving sustainable growth in future periods.
