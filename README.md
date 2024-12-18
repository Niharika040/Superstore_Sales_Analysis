# Superstore_Sales_Analysis


## Project Overview
This project is an **exploratory and descriptive analysis** of the **Superstore Dataset**, sourced from **Kaggle**. The dataset provides rich insights into business operations, including sales, profit, customer segmentation, and regional performance. The analysis leverages advanced **Excel tools**, including Pivot Tables, Data Visualizations, and Formula-based calculations, to uncover hidden patterns and key metrics that drive business performance. The primary goal is to transform raw data into actionable insights that can help in strategic decision-making across various aspects of the business.


---

## Project Goals

The project aims to uncover key business insights through descriptive and exploratory data analysis, leveraging advanced Excel tools and visualizations. Some of the goals include identifying sales trends, profit distribution, customer segmentation, and understanding operational efficiency. By visualizing these insights, this project supports strategic decision-making, optimizes business processes, and helps in identifying opportunities for growth and improvement in sales performance.

This repository showcases various data visualizations and analyses created in Excel. The charts are categorized into descriptive, time-based, regional, and other analytical themes for easy navigation. For a more detailed analysis, explore the visualizations and insights in the repository.

Key Excel Features Used:

- Data Cleaning and Preprocessing
- Formulas and Functions
- PivotTables and PivotCharts
- Conditional Formatting
- Data Visualization

The raw data used in this analysis was sourced from Kaggle’s Superstore Sales Dataset. You can download the dataset using the link below:
[link: Kaggle Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting/code)

 
## Steps Involved in Analysis

### 1. Data Preparation

Before performing any analysis, the dataset needs to be cleaned and formatted properly. The steps involved include:
- No missing and duplicated values were found.
- Formatting date columns to ensure proper time series analysis.
- Creating new columns [highlighted by Green color] such as calculating the "Delivery Time" from Order Date to Ship Date, profit margin, etc.

  **Cleaned Dataset**
   [cleaned_dataset](./cleaned_sales_data.xlsx)
  


### 2. EDA


All the charts and analysis can be found in the [Superstore_Sales_Analysis](./Superstore_Sales_Analysis.xlsx) file in this repository. You can easily explore the data and charts by navigating through the different sheets in the file.
Charts and insights categorized as follows:

1. **Descriptive Analysis**: Sales and Profit by Subcategory, Profit Margin Analysis, etc.
2. **Time-Based Analysis**: Sales Trend Over Time, Average Delivery Time Across Regions.
3. **Regional Analysis**: Profit and Sales by Region, Top 10 States and Cities by Revenue.
4. **Discount and Profit Analysis**: Impact of Discount on Sales and Profit.
5. **Customer and Product Analysis**: Sales and Profit by Customer Segment, Highest Revenue-Generating Product.
6. **Revenue Breakdown**: Breakdown by Category/Subcategory, Profit to Sales Ratio.
7. **Future Prediction**: Future Sales Prediction and Confidence Intervals.


**2.1 Insights from Descriptive Analysis and Interpretation**

  - The analysis of the Superstore dataset provides actionable insights into sales, profitability, and customer behavior for portfolio optimization. High-performing subcategories like Copiers, Paper, Labels, and Envelopes exhibit strong profit margins (37%-44%), while Tables (-9%), Supplies (-3%), and Bookcases (-3%) incur losses, indicating pricing or operational inefficiencies.
  - Technology leads sales (36.4%), followed by Furniture (32.3%) and Office Supplies (31.3%), with low-performing subcategories like Machines (2%) and Bookcases requiring strategic adjustments. Standard Class dominates sales (59%), though premium shipping modes like Same Day and First Class deliver higher profitability.
  -  Regions such as California, Texas, and New York lead revenue, while Wyoming and West Virginia remain untapped opportunities. The Consumer segment drives over 50% of orders, but Corporate and Home Office segments remain underutilized, suggesting potential for targeted campaigns.
  -   Discounting impacts profitability, with excessive discounts in Furniture and Tables eroding margins, while high-margin categories like Paper and Labels balance value and profit.
  -   Office Supplies account for 60% of quantities but yield lower margins, contrasting with the high-margin impact of Technology. Prioritizing profitable subcategories, optimizing discounts, expanding premium shipping, and targeting untapped regions and segments can drive growth and profitability

**2.2 Insights from Time-based Analysis and Interpretation**

- **Sales Peak in the Last Quarter:** Sales tend to be highest in the **last quarter** of the year (October, November, December), particularly in **2016** and **2017**.
- **November Sales Spike:** There is a consistent **spike in sales in November** across all years, likely due to **Black Friday** and **holiday shopping**.
- **Same Day and First Class Delivery:** The quickest delivery options are **Same Day (0 days)** and **First Class (2 days)**, which are ideal for customers seeking **fast deliveries**.
- **Second Class and Standard Class Delivery:** These options have **longer average times** (3 and 5 days, respectively), which may negatively impact **customer satisfaction** and **sales**, particularly during **peak seasons**.

 **A. Sales Performance vs. Delivery Time**

- **2014:** Sales were moderate at $484K, and Standard Class delivery time was 5 days, which could have led to slower customer responses during peak months.

- **2015:** Sales dropped slightly to $470K, potentially due to the 5-day delivery of Standard Class, which in a competitive market could have deterred customers. While Same Day delivery (0 days) would have been optimal, it was likely not as common.
- **2016:** Sales rose to $609K, correlating with the availability of faster delivery options (e.g., Same Day and First Class), which likely enhanced customer satisfaction.
- **2017:** Sales peaked at $733K, aligning with the increased availability of quick delivery options across regions. November saw the highest sales, where faster delivery likely played a key role.
  
**B. Monthly Sales vs. Delivery Times:**

- **January - March:** Sales were lower during these months, likely due to post-holiday spending drops. Delivery times across regions remained consistent with Standard Class (5 days) being the dominant option, though Same Day (0 days) and First Class (2 days) were likely less common during these slower months.
  
- **April - September:** Sales were moderate, with delivery times still hovering between 2 and 5 days. There was no noticeable surge in sales, but Same Day and First Class deliveries could potentially boost sales during these mid-year lulls.
  
- **October - December:** Sales peaked, especially in November and December. During these busy months, faster delivery options (Same Day, First Class) likely became more critical. Faster delivery options seemed to correlate with higher sales, as customers prioritized quick shipments during the holiday season.


**2.3 Insights from Regional Analysis Analysis and Interpretation**
California (West region) leads in sales revenue with $457,687.63, significantly surpassing New York ($310,876.27) and Texas ($170,188.05). These three states contribute substantially to total sales, driven by their large populations and economic activity.

- At the city level, New York City (East region) tops with $256,368.16, followed by Los Angeles ($175,851.34) and Seattle ($119,540.74), highlighting urban hubs as key revenue drivers.

- California also delivers strong profits ($76,381.39), showcasing effective cost management and market demand. In contrast, states like New York and Florida, despite high sales, report negative profits, likely due to high COGS, operational inefficiencies, or market saturation.

- States like Georgia ($16,250.04), Michigan ($24,463.19), and Washington ($33,402.65) achieve positive profits, reflecting efficient cost control and healthy margins.

- This analysis reveals notable discrepancies between sales and profits, particularly in states like **New York** and **Florida**, where high sales figures do not correspond to high profits. Such issues may be attributed to higher costs of goods sold (**COGS**), operational inefficiencies, or external factors like increased competition or market saturation. 

- In contrast, **California**, **Michigan**, and **Washington** show a strong correlation between high sales and high profits, suggesting effective cost management and strategic market positioning in these regions. However, larger states like **Texas** and **New York**, despite their impressive sales figures, also face significant profit challenges. These challenges may stem from high competition, logistical costs, or underperforming sectors within these regions, ultimately impacting their overall profitability.


**2.4 Insights from Discount and Profit Analysis and Interpretation**

- The data shows that discounts have a minimal impact on sales across all categories. Furniture, Office Supplies, and Technology have discounts as a percentage of sales of 0.05%, 0.13%, and 0.03%, respectively, with the overall discount across all categories being just 0.07% of total sales.
- This suggests that discounts play a very minor role in driving sales, and other factors such as product quality, branding, or customer loyalty are likely more significant contributors. The low percentage of discount relative to sales indicates a strategy that focuses more on maintaining profitability and positioning products at their value rather than relying heavily on discounting.

- Profit margins are strongest at 0% discount (34.02%) and decline sharply beyond 30%, turning negative at 40% or higher. While Technology remains resilient to moderate discounts, Furniture and Office Supplies face significant margin erosion at high discount levels. To optimize performance, the business should focus on low to moderate discounting (0–20%), avoid deep discounts, and enhance value through strategic pricing, bundling, and targeted promotions tailored to category-specific demand patterns.

**2.5 Insights from Customer and Product Analysis and Interpretation**

- In terms of customer segments, the **Consumer** segment leads with the highest sales ($1,161,401.35) and profit ($134,119.21), indicating a strong revenue-generating and profitable customer base. The **Corporate** segment follows with $706,146.37 in sales and $91,979.13 in profit, showing a solid contribution but at a lower profitability rate compared to the Consumer segment. The **Home Office** segment has the lowest sales ($429,653.15) and profit ($60,298.68), suggesting that this customer segment, while still significant, is less impactful in terms of both revenue and profit.

- Looking at the product analysis, the **Canon imageCLASS 2200 Advanced Copier** generates the highest revenue ($61,599.82), followed by the **Fellowes PB500 Electric Punch Plastic Comb Binding Machine** with $27,453.38, and the **Cisco TelePresence System EX90 Videoconferencing Unit** at $22,638.48. This suggests that products related to office equipment and technology play a key role in driving sales, particularly in categories like copiers, printers, and binding systems.

- Together, these findings indicate that the Superstore's strategy might benefit from focusing on expanding offerings within these high-performing customer segments and product categories to maximize revenue and profit.

**2.6 Insights from Revenue Breakdown Analysis and Interpretation**
  
- The total sales revenue from the Superstore dataset amounts to **$2,297,200.86**, with significant contributions from different product categories and subcategories. 

- **Technology** leads with the highest sales of **$836,154.03**, followed by **Furniture** at **$741,999.80** and **Office Supplies** at **$719,047.03**.
  
- In terms of subcategories, **Chairs** within the Furniture category contribute the highest sales at **$328,449.10**, followed by **Binders** at **$203,412.73** and **Copiers** at **$149,528.03**. Other notable subcategories include **Accessories** with **$167,380.32** and **Storage** with **$223,843.61**. 

- These findings suggest that **Technology** and **Furniture** are the dominant categories in terms of revenue, with subcategories such as **Chairs**, **Binders**, and **Storage** making key contributions.
  
- The **Profit to Sales Ratio** analysis provides insight into the efficiency of sales in terms of profitability across different ranges. 

- The **0-10% range** shows the highest profitability with a ratio of **0.29**, contributing **$1,142,277.82** in sales and **$330,016.78** in profit. This indicates that the majority of sales within this range are generating positive profits.
  
- However, as the ratio increases beyond 20%, the profitability decreases, with negative ratios observed in the **20-30%**, **30-40%**, and higher ranges, which correspond to declining profits despite the sales. This indicates that higher discount ranges are associated with lower profit margins or losses.

- In summary, the **Technology** and **Furniture** categories dominate sales, with subcategories like **Chairs**, **Binders**, and **Storage** contributing significantly to overall revenue. However, when examining profitability in relation to sales, a clear trend emerges: higher discount ranges are linked with reduced profit margins. The **0-10% profit-to-sales ratio** range shows the most favorable balance between sales and profit, suggesting that more moderate discounting strategies may lead to healthier profit margins. As the discount percentage increases, the profitability decreases, with negative ratios observed in higher discount ranges, implying that larger discounts are hurting profitability.

- The Superstore's strategy might benefit from a more focused approach on offering higher-margin products in the **Technology** and **Furniture** categories, while managing discount strategies carefully to avoid margin erosion in higher discount bands. The data indicates that maintaining moderate discounts may strike a better balance between sales and profit generation.



**2.7 Insights from Future prediction  and Interpretation**

 - The chart displays a time series analysis of sales and order processing times, with the blue line representing actual data and the orange line depicting the forecast. The shaded area between the orange lines represents the confidence intervals, which indicate the level of uncertainty in the forecast.
 - The actual data reveals a gradual upward or downward trend, which could be linked to changing sales volumes, order complexity, or other external factors. The forecast generally aligns with the historical data, demonstrating the model's effectiveness in predicting future sales and order processing times.
 - However, as the forecast period extends, the confidence intervals widen, highlighting an increase in uncertainty. This suggests that while the model can provide reasonably accurate short-term predictions, it becomes less reliable for long-term forecasts due to the potential influence of external variables. It emphasizes the importance of monitoring real-time data and adjusting business strategies accordingly to manage unforeseen changes in sales trends.




## Recommendation 

**Optimize Product Portfolio for Profitability:** Focus on high-margin subcategories like Copiers, Paper, Labels, and Envelopes (37%-44% profit margins) while addressing loss-making categories such as Tables, Supplies, and Bookcases. Reassess pricing and operational strategies to improve profitability in underperforming segments.

**Leverage High-Performing Categories:** Prioritize investment in Technology and Furniture, which lead sales revenue, while expanding profitable subcategories like Chairs, Binders, and Storage. Diversify product offerings in high-demand and high-margin items within these categories.

**Adjust Discount Strategies:** Maintain discounts in the 0-20% range, where profitability is highest. Avoid deep discounting beyond 30%, which results in negative margins. Instead, adopt strategic pricing, bundling, and value-driven promotions to retain profitability without eroding margins.

**Enhance Regional Targeting:** Build on strong-performing regions like California, Texas, and New York while tapping into untapped markets such as Wyoming and West Virginia. Address profitability challenges in high-sales but low-profit regions (e.g., New York and Florida) through cost control and operational efficiency improvements.

**Improve Shipping Strategies:** Expand premium shipping options like Same Day and First Class, which enhance customer satisfaction and correlate with higher sales during peak periods. Reduce delivery times for Standard Class to improve competitiveness and retain customer loyalty.

**Capitalize on Consumer Segment:** The Consumer segment drives the majority of sales and profits. Focus marketing efforts here while targeting untapped potential in Corporate and Home Office segments through tailored campaigns and value-added services.

**Seasonal Sales Focus:** Leverage the consistent sales spike in November and the last quarter of the year by optimizing inventory, enhancing delivery speed, and running targeted promotions to maximize holiday shopping trends.

**Strategic Investments in High-Performing Products:** Promote top-performing products like Canon imageCLASS Copiers and Cisco TelePresence Units, which drive significant revenue. Expand offerings in similar high-demand office equipment and technology products.

**Expand High-Margin Office Supplies:** Office Supplies dominate quantities sold but yield lower margins. Focus on promoting high-margin items like Paper and Labels while reevaluating the profitability of bulk items within this category.

By implementing these recommendations, the Superstore can maximize sales, improve profitability, and enhance customer satisfaction while addressing inefficiencies across categories, regions, and customer segments.

## **About Me**
I am an Excel and data visualization enthusiast with expertise in analyzing and presenting insights from large datasets. This portfolio reflects my experience in creating impactful visualizations for business intelligence.




