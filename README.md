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

## Steps Involved in Analysis

### 1. Data Preparation

Before performing any analysis, the dataset needs to be cleaned and formatted properly. The steps involved include:
- No missing and duplicated values were found.
- Formatting date columns to ensure proper time series analysis.
- Creating new columns [ higlighted by Green color] such as calculating the "Delivery Time" from Order Date to Ship Date, profit margin etc.

  ### Cleaned Dataset
  -**File Name**:-[Cleaned dataset]


     
### 2. Exploratory Data Analysis (EDA)

#### Descriptive Analysis

##### Sales and Profit Analysis by Subcategory

Sales and profit analysis by subcategory provides a clear understanding of how each product subcategory is performing in terms of revenue and profitability.

- **Chairs** emerges as the top revenue generator, contributing **$328,449.10** in sales, while **Copiers** stands out as the most profitable subcategory, with **$55,617.82** in profit.

- Some subcategories, such as **Supplies**  and **Tables**, show negative profits, highlighting underperformance and areas for potential reassessment.

- Despite these losses, the overall profit across all subcategories remains strong at **$286,397.02**, driven by high-performing categories like **Binders**, **Phones**, and **Storage**, which significantly contribute to both sales and profit.

- Additionally, subcategories like **Art** and **Envelopes**, although generating lower sales, maintain strong profit margins, suggesting they are niche but high-margin items.
  
##### **Profit Margin Analysis by Subcategory**

This analysis focuses on the profit margins achieved by each subcategory in the Superstore dataset. Profit margin is a critical metric that indicates the profitability of a product or category as a percentage of sales. This analysis helps in identifying high-margin and low-margin subcategories, enabling better decision-making regarding pricing, marketing, and inventory strategies.

- High-performing subcategories such as **Labels** (44%), **Paper** (43%), and **Envelopes** (42%) demonstrate exceptional efficiency in converting sales into profit, making them ideal candidates for further investment and promotional efforts. Additionally, subcategories like **Copiers** (37%) and **Fasteners** (31%) exhibit strong profit margins, highlighting their potential for growth and strategic prioritization.

- Moderate performers, including **Accessories** (25%), **Art** (24%), and **Appliances** (17%), maintain respectable profitability and could benefit from targeted marketing strategies to enhance their revenue potential. On the other hand, low-margin subcategories like **Machines** (2%) and **Chairs** (8%) may require a review of their pricing structures and operational costs to improve profitability.

- Subcategories with negative margins, such as **Bookcases** (-3%), **Supplies** (-3%), and **Tables** (-9%), demand immediate attention to address underlying issues, such as high costs or over-discounting, to mitigate losses and enhance overall business performance.


  ##### **Sales Distribution by Category**

The sales distribution is categorized into three primary segments: Furniture, Office Supplies, and Technology. The percentages represent the share of total sales contributed by each category.


- **Technology** leads with the highest sales contribution (36.40%), indicating its critical role in driving overall revenue. This suggests a robust demand for technology products, which warrants sustained inventory management and marketing focus.
- **Furniture** and **Office Supplies** contribute almost equally, with 32.30% and 31.30%, respectively. While these categories are slightly behind Technology, their significant share highlights the need for strategic efforts to maintain competitive positioning.
- The close distribution among the three categories indicates a balanced revenue stream, reducing over-reliance on any single segment.


### **Count of Ship Mode**

The dataset provides the count of shipments for each U.S. state, representing the distribution of shipping activities across the country.

- **California** accounts for the highest shipping activity with 2001 shipments, reflecting its significant consumer base and business operations, followed by **New York** with 1128 shipments, indicating high demand for products and shipping services, and **Texas** with 985 shipments, emphasizing its role as a major hub for commerce and distribution.
  
- States like **Florida**, **Illinois**, **Pennsylvania**, and **Washington** show substantial shipping activity, which highlights their importance as regional markets.

- States like **Wyoming**, **West Virginia**, **North Dakota**, and **Maine** show minimal shipping activity, which may reflect lower population density or limited market penetration in these areas.

 - Coastal states such as **California**, **New York**, and **Florida** dominate shipping volumes due to their large economies and significant population centers.
   - Central and sparsely populated states such as **Wyoming** and **North Dakota** contribute the least to shipping activities.















   - **Sales and Profit by Ship Mode**
   - **Count of Customer ID**
   - **Total Quantity Ordered by Category**
   - **Segment Count Analysis by Subcategory**

---

### **2. Time-Based Analysis**
   - **Sales Trend Over Time**
   - **Average Delivery Time Across Regions**

---

### **3. Regional Analysis**
   - **Regional Profit Distribution (%)**
   - **Geographic Profit Analysis**
   - **Top 10 States by Sales Revenue**
   - **Top Cities by Sales Revenue**

---

### **4. Discount and Profit Analysis**
   - **Category-Wise Distribution of Discount and Value**
   - **Impact of Discount on Sales Across Product Categories**
   - **Effect of Discount on Profit Margin**
   - **Sales and Profit by Discount Range**

---

### **5. Customer and Product Analysis**
   - **Sales and Profit by Customer Segment**
   - **Highest Revenue-Generating Product**

---

### **6. Revenue Breakdown**
   - **Revenue Breakdown by Category and Subcategory**
   - **Profit-to-Sales Ratio**

---

## **Sample Chart Previews**

### Example: Sales Trend Over Time
- **Description**: Line chart displaying total sales across months to identify seasonal trends.
- **Key Insights**: Highlight peak sales months and dips.
![Sales Trend Example](https://via.placeholder.com/800x400.png?text=Sample+Sales+Trend)

---

### Example: Regional Profit Distribution (%)
- **Description**: Pie chart showcasing profit contribution from each region as a percentage.
- **Key Insights**: Helps identify the most profitable regions.
![Regional Profit Example](https://via.placeholder.com/800x400.png?text=Regional+Profit+Distribution)

---

## **How to Use These Charts**
- Open the Excel file containing your dataset.
- Use the chart types mentioned above to replicate the visualizations.
- Customize based on your dataset to derive actionable insights.

---

## **About Me**
I am an Excel and data visualization enthusiast with expertise in analyzing and presenting insights from large datasets. This portfolio reflects my experience in creating impactful visualizations for business intelligence.

---

## **Connect**
- [LinkedIn](https://linkedin.com)
- [GitHub](https://github.com/YourUsername)


