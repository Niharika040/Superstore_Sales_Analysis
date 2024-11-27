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

- Some subcategories, such as **Supplies** (**$46,673.54** in sales, **-$1,189.10** in profit) and **Tables** (**$206,965.53** in sales, **-$17,725.48** in profit), show negative profits, highlighting underperformance and areas for potential reassessment.

- Despite these losses, the overall profit across all subcategories remains strong at **$286,397.02**, driven by high-performing categories like **Binders** (**$203,412.73** in sales, **$30,221.76** in profit), **Phones** (**$330,007.05** in sales, **$44,515.73** in profit), and **Storage** (**$223,843.61** in sales, **$21,278.83** in profit), which significantly contribute to both sales and profit.

- Additionally, subcategories like **Art** (**$27,118.79** in sales, **$6,527.79** in profit) and **Envelopes** (**$16,476.40** in sales, **$6,964.18** in profit), although generating lower sales, maintain strong profit margins, suggesting they are niche but high-margin items.

---

This analysis provides valuable insights into which product subcategories are driving overall business performance and which areas require further attention and strategic improvement.

### Recommendations

To optimize business performance and profitability, it is recommended to focus on high-performing subcategories such as **Chairs**, **Phones**, and **Copiers** by prioritizing their marketing and inventory management. These subcategories are contributing significantly to overall sales and profits, and increasing their visibility can drive further revenue growth.

For underperforming subcategories like **Supplies** and **Tables**, a thorough evaluation of pricing strategies, promotions, or potential product replacements is necessary. Addressing these areas can help mitigate losses and improve profitability.

Additionally, products with high profit margins but lower sales, such as **Art** and **Envelopes**, should be promoted more strategically to capitalize on their profitability. By increasing their sales volume, the business can further enhance its overall profit margins.

Cross-selling opportunities for products with high sales but lower margins, like **Phones** and **Binders**, could further improve profit. This approach can help increase the profitability of existing products while enhancing the customer experience.

Finally, diversifying product offerings in successful categories such as **Chairs** and **Storage** would also be beneficial. Expanding these high-performing categories can help the business capture more market share and create new revenue streams.

Implementing these strategies will help increase profitability, streamline inventory management, and ensure long-term growth.




   

   
   - **Profit Margin Analysis by Subcategory**
   - **Sales Distribution by Category**
   - **Count of Ship Mode**
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


