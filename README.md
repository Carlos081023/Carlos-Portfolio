# Sales Analysis Project

## User Story: Sales Performance Insights

A retail company specializing in office supplies, technology products, and furniture seeks to gain a deeper understanding of its current sales performance. The management team aims to uncover specific insights across their three key departments to inform decision-making and guide future strategies.
Key Business Questions:

  * How has the business performed year-over-year (YoY) in sales, profit, and quantity sold?
  * Which product categories and subcategories drive the most revenue and profit?
  * Are there regional trends or patterns in sales performance across different locations?
  * What impact do discounts and promotions have on overall sales and profitability?
  * Which customer segments are the most profitable, and how can they be better targeted?
  * Are there seasonal patterns or specific periods where sales spike or decline?

The management team seeks to uncover YoY growth trends, identify best-selling products, and analyze regional sales variations to make data-driven decisions around marketing strategies for the upcoming year. Additionally, they want to forecast future sales to support long-term planning.

## Business Objectives

  * Reveal key sales insights by department (Office Supplies, Technology, Furniture).
  * Understand sales and profit trends at a granular level: by product category, customer segment, and region.
  * Analyze the impact of discounts and promotions on sales and profitability.
  * Identify seasonal patterns or trends across regions or product categories.
  * Provide actionable recommendations to improve sales growth and marketing efforts.
  * Build a dynamic dashboard for management to facilitate quick decision-making.

## Data Collection
The dataset includes four CSV files: Orders, Customers, Products, and Location. The Orders file details transactions over five years (2018–2023). The Customers file contains customer information such as location and name, while the Products file lists all SKUs the company currently offers. The Location file includes address information within the United States.

## Data Cleaning

The dataset required processing and cleaning to ensure quality, focusing on:

  * Correcting text/spelling errors.
  * Standardizing labels, formats, and field lengths.
  * Removing duplicates.
  * Handling missing or blank values.

Data integrity is crucial to accurate analysis. The complete data cleaning process is documented in the file here.

## Data Analysis and Visualization

After structuring the data model in Tableau (Refer to this for more explanation), analysis began to address core business questions and additional insights. To visit the Sales Dashboard click this link.
Top Performing Products by Sales:


Using a PivotTable, the top 5 products by sales generated a combined $153K. Office Supplies and Technology were popular categories, with only one Furniture item among the top five, indicating stronger consumer interest in Office Supplies and Technology.
Customer Order Behavior Analysis:


An analysis of order size, frequency, and average order value (AOV) over four years revealed that while average order quantity remained stable, AOV peaked in 2020 and then declined. This suggests an opportunity for strategies, like bundling or upselling, to boost AOV.
Further analysis of the top 10 customers by order frequency showed that a high transaction count does not guarantee profitability. While frequent buyers purchased more units, those with fewer transactions sometimes contributed more to revenue and profit.
Sales Trend Analysis:

A PivotChart revealed that autumn consistently generated the highest revenue, peaking in September and November, while winter, particularly February, saw a dip in revenue. Sales showed an upward trend, signaling overall company growth.
Year-Over-Year Growth Analysis:
Using 2020 as a baseline, the company experienced a slight revenue dip in 2021 but saw growth in profits and units sold. From 2021 onward, all key metrics—sales, profit, and units sold—showed positive growth, with cumulative revenue reaching $2.2 million, $286,397 in profit, and sold 37,873 units by 2023.

### Sales by Category and Sub-Category:
Furniture: Chairs and Furnishings showed consistent profitability, while Tables and Bookcases often incurred losses, suggesting a need to revisit discount strategies or bundling options.
Office Supplies: This category generally performed well, with Storage, Binders, and Paper consistently profitable. The Supplies subcategory, however, showed minimal negative impact on overall profits.
Technology: The top-performing category with steady growth across years, though Machines and Phones faced occasional profit issues, particularly in years with high discounts.

### Sales by Region:
The analysis found that California, Texas, New York, Florida, and Washington consistently drove top sales.
California: High demand for technology and furniture items, such as mobile phones and chairs, with underperforming subcategories like art supplies. Strategy adjustments should emphasize popular products to boost overall profitability.
New York: Strong focus on Technology, with consistent YoY growth except for a minor dip in 2022 due to reduced autumn sales.
Texas: Frequent reliance on discounts has resulted in negative profits. Texas could benefit from a strategic reevaluation of its discount structure.
Florida: Increasing interest in Technology and Furniture, though profitability suffers due to discount dependence.
Washington: Underperformed until 2023, which saw a strong recovery, particularly in March, marking a turning point in the region's sales performance.

### Impact of Discounts:
While discounts drive sales, excessive reliance on them can harm profitability. For example, heavy discounts on Tables have consistently led to negative profit margins. Strategic discounting, particularly on underperforming items, and exploring bundling options could better balance revenue with profitability.

### Seasonality on Sales /  Sales Over Time:
Sales over time has seen a major spike in the Autumn season, more specifically in September and November months. These two months generate the most revenue for the company consistently every year, for example November of 2023 saw the best performance across all years in terms of sales with a staggering $118k in total revenue.
There is also another small uptick in March following the sharp decline in sales in the Winter season. Additionally, for every year, Feburary has performed the worst in terms of sales however it steadily rises every year. 
Off-Peak months are centered in the Winter season, namely January and Feburary with some Spring and Summer months also seeing a cooldown in sales although not the in same magnitude as the Winter season.


### Dashboard Overview:

	
The Sales Dashboard gives the management team the ability to quickly spot key metrics such as Total Sales, Profit, Quantity sold, and Total discount amount accrued year over year with comparison to the previous year for a better understanding into the performance of each metric. Visualizations also offer the ability to quickly understand region performance, trend analysis, and sub category performance for quick insights and action wherever needed.

The second dashboard is a customer over into the 10 top customers by profitability. This will give management the ability to quickly gain insights into the behavior of our profitable customers to better market products and keep high-value customers.

### Actionable Recommendations:

  * Adjust Discount Strategy: Reduce discounts on loss-incurring items, like Tables, to mitigate profit erosion. Bundling high-demand items with discounted items could help balance profits.

  * Customer Loyalty Program: Implement a loyalty program targeting high-value customers, especially within the Consumer segment, to foster repeat purchases and strengthen customer retention.
    
  * Boost Average Order Value (AOV): Employ bundling and upselling strategies to increase AOV. For example, pairing products with complementary items can encourage customers to spend more.
