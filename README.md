# Superstore_Sales_Analysis


## Project Overview
This project is an **exploratory and descriptive analysis** of the **Superstore Dataset**, sourced from **Kaggle**. The dataset provides rich insights into business operations, including sales, profit, customer segmentation, and regional performance. The analysis leverages advanced **Excel tools**, including Pivot Tables, Data Visualizations, and Formula-based calculations, to uncover hidden patterns and key metrics that drive business performance. The primary goal is to transform raw data into actionable insights that can help in strategic decision-making across various aspects of the business.

 
The dataset contain following key attributes:
- **Row ID**: A unique identifier for each row in the dataset.
- **Order ID**: A unique identifier for each order.
- **Order Date**: The date when the order was placed.
- **Ship Date**: The date when the order was shipped.
- **Customer ID**: A unique identifier for each customer.
- **Customer Name**: The name of the customer.
- **Segment**: The segment to which the customer belongs (e.g., Consumer, Corporate, Home Office).
- **Country**: The country where the order was placed.
- **City**: The city where the order was placed.
- **State**: The state within the country where the order was placed.
- **Postal Code**: The postal code of the customer's location.
- **Region**: The region (e.g., East, West, Central) within the country where the order was placed.
- **Product ID**: A unique identifier for each product.
- **Category**: The category to which the product belongs (e.g., Furniture, Office Supplies, Technology).
- **Sub-Category**: A more specific classification of the product (e.g., Chairs, Binders, Phones).
- **Product Name**: The name of the product.
- **Sales**: The total sales amount for the order.
- **Quantity**: The number of products ordered.
- **Discount**: The discount applied to the order.
- **Profit**: The profit generated from the order.
- **Ship Mode**: The shipping method used (e.g., Standard Class, Second Class, First Class, Same Day).

---

## Project Goals

The project aims to uncover key business insights through descriptive and exploratory data analysis, leveraging advanced Excel tools and visualizations. Some of the goals include identifying sales trends, profit distribution, customer segmentation, and understanding operational efficiency. By visualizing these insights, this project supports strategic decision-making, optimizes business processes, and helps in identifying opportunities for growth and improvement in sales performance.

This repository showcases various data visualizations and analyses created in Excel. The charts are categorized into descriptive, time-based, regional, and other analytical themes for easy navigation. For a more detailed analysis, explore the visualizations and insights in the repository.

The raw data used in this analysis was sourced from Kaggle’s Superstore Sales Dataset. You can download the dataset using the link below:
[link: Kaggle Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting/code)

 The Excel file `Superstore_Sales_Analysis.xlsx` contains multiple charts and insights categorized as follows:

1. **Descriptive Analysis**: Sales and Profit by Subcategory, Profit Margin Analysis, etc.
2. **Time-Based Analysis**: Sales Trend Over Time, Average Delivery Time Across Regions.
3. **Regional Analysis**: Profit and Sales by Region, Top 10 States and Cities by Revenue.
4. **Discount and Profit Analysis**: Impact of Discount on Sales and Profit.
5. **Customer and Product Analysis**: Sales and Profit by Customer Segment, Highest Revenue-Generating Product.
6. **Revenue Breakdown**: Breakdown by Category/Subcategory, Profit to Sales Ratio.


## Steps Involved in Analysis

### 1. Data Preparation

Before performing any analysis, the dataset needs to be cleaned and formatted properly. The steps involved include:
- No missing and duplicated values were found.
- Formatting date columns to ensure proper time series analysis.
- Creating new columns [highlighted by Green color] such as calculating the "Delivery Time" from Order Date to Ship Date, profit margin, etc.

  ### Cleaned Dataset
  -**File Name**:-[Cleaned dataset]


### 2. EDA


All the charts and analysis can be found in the **Superstore_Sales_Analysis.xlsx** file in this repository. You can easily explore the data and charts by navigating through the different sheets in the file.


**2.1 Insights from Descriptive Analysis and Interpretation**

   - The comprehensive analysis of the Superstore dataset reveals valuable insights across subcategories, categories, shipping modes, customer segments, regional performance, and the impact of discounts on sales and profit margins.

   - Subcategory analysis highlights significant disparities in performance. While Copiers, Paper, and Labels demonstrate exceptional profitability with profit margins exceeding 40%, categories like Tables (-9%) and Supplies (-3%) generate losses despite moderate sales volumes, indicating operational inefficiencies or misaligned pricing strategies.
     
   - The Technology category dominates overall sales, contributing 36.4% of total revenue, closely followed by Furniture (32.3%) and Office Supplies (31.3%), reflecting diverse customer preferences. However,low-performing subcategories such as Machines and Bookcases present opportunities for reevaluation and repositioning.

   - Shipping modes show varying utilization and profitability. Standard Class is the most utilized, contributing the majority of sales, whereas First Class and Same Day services, despite their smaller share, exhibit higher profitability, suggesting potential for premium targeting. In customer segmentation, the Consumer segment accounts for over 50% of orders, but there is untapped potential in the Corporate and Home Office segments, which could benefit from customized offerings.

   - Regional analysis underscores the dominance of states like California, Texas, and New York, which are the largest revenue contributors. Conversely, states like Wyoming and West Virginia exhibit minimal sales activity, representing untapped market opportunities. The correlation between regions, shipping modes, and customer segments could be leveraged to enhance performance in underperforming areas.

  - Discount analysis reveals a direct impact on profitability. Excessive discounting in categories like Tables and Furniture correlates with significant profit erosion, emphasizing the need for more strategic discount management. Subcategories like Envelopes, Paper, and Labels, which maintain high-profit margins despite discounts, highlight opportunities to balance value and profitability.

  - Lastly, the analysis of total quantity ordered reinforces the dominance of Office Supplies, accounting for 60% of total quantities, but with relatively low margins. This contrasts with the high-margin contributions of the Technology category, which, despite lower quantities, significantly bolsters overall profitability.

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

- California leads the states with the highest sales revenue, reaching **$457,687.63**, significantly surpassing other states like New York (**$310,876.27**) and Texas (**$170,188.05**). These top three states contribute a substantial portion of total sales, demonstrating that the most populous and economically active regions are driving a major share of the revenue. 

- On the city level, **New York City** tops the list with **$256,368.16** in sales, outpacing major cities such as **Los Angeles** (**$175,851.34**) and **Seattle** (**$119,540.74**), highlighting the importance of urban hubs in driving high sales.

- In addition to leading in sales, California also delivers a strong profit of **$76,381.39**, suggesting efficient cost management and robust market demand. In contrast, states like **New York** and **Florida**, despite generating high sales, report negative profits. This discrepancy implies that while these states are successful in driving revenue, operational costs or pricing strategies may be hindering profitability. 

- On the other hand, states such as **Georgia** (**$16,250.04**), **Michigan** (**$24,463.19**), and **Washington** (**$33,402.65**) demonstrate positive profits, indicating they are not only making strong sales but also managing their costs efficiently, resulting in healthier margins.

- This analysis reveals notable discrepancies between sales and profits, particularly in states like **New York** and **Florida**, where high sales figures do not correspond to high profits. Such issues may be attributed to higher costs of goods sold (**COGS**), operational inefficiencies, or external factors like increased competition or market saturation. 

- In contrast, **California**, **Michigan**, and **Washington** show a strong correlation between high sales and high profits, suggesting effective cost management and strategic market positioning in these regions. However, larger states like **Texas** and **New York**, despite their impressive sales figures, also face significant profit challenges. These challenges may stem from high competition, logistical costs, or underperforming sectors within these regions, ultimately impacting their overall profitability.


**2.4 Insights from Discount and Profit Analysis and Interpretation**

- The data shows that discounts have a minimal impact on sales across all categories. Furniture, Office Supplies, and Technology have discounts as a percentage of sales of 0.05%, 0.13%, and 0.03%, respectively, with the overall discount across all categories being just 0.07% of total sales.
- This suggests that discounts play a very minor role in driving sales, and other factors such as product quality, branding, or customer loyalty are likely more significant contributors. The low percentage of discount relative to sales indicates a strategy that focuses more on maintaining profitability and positioning products at their value rather than relying heavily on discounting.

  **2.5 Insights from Customer and Product Analysis and Interpretation**
  ### Sales and Profit Analysis by Customer Segment and Product Performance

- In terms of customer segments, the **Consumer** segment leads with the highest sales ($1,161,401.35) and profit ($134,119.21), indicating a strong revenue-generating and profitable customer base. The **Corporate** segment follows with $706,146.37 in sales and $91,979.13 in profit, showing a solid contribution but at a lower profitability rate compared to the Consumer segment. The **Home Office** segment has the lowest sales ($429,653.15) and profit ($60,298.68), suggesting that this customer segment, while still significant, is less impactful in terms of both revenue and profit.

- Looking at the product analysis, the **Canon imageCLASS 2200 Advanced Copier** generates the highest revenue ($61,599.82), followed by the **Fellowes PB500 Electric Punch Plastic Comb Binding Machine** with $27,453.38, and the **Cisco TelePresence System EX90 Videoconferencing Unit** at $22,638.48. This suggests that products related to office equipment and technology play a key role in driving sales, particularly in categories like copiers, printers, and binding systems.

- Together, these findings indicate that the Superstore's strategy might benefit from focusing on expanding offerings within these high-performing customer segments and product categories to maximize revenue and profit.


## **About Me**
I am an Excel and data visualization enthusiast with expertise in analyzing and presenting insights from large datasets. This portfolio reflects my experience in creating impactful visualizations for business intelligence.




