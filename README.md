# Amazon Sales Data Analysis

# Introduction
Amazon, Inc. serves as a major e-commerce platform where merchants globally engage in selling a diverse range of products. As part of their business operations, merchants often export their sales data from the Amazon portal for further analysis. This project aims to conduct a comprehensive analysis of the sales data obtained from the merchant's Amazon account, stored in the 'sales_data.xlsx' file.

# Table of Contents
- Data Understanding
- Data Preparation
- Exploratory Data Analysis
- Conclusion

# Data Understanding
The initial step involves understanding the data to gain insights into its structure and content. This includes:

- Previewing the first and last rows of the dataset.
- Checking for any random rows to ensure data quality.
- Determining the shape of the dataset (number of rows and columns).
- Displaying all columns of the dataset.
- Providing information on data types and memory usage.
- Offering a descriptive statistics summary.

# Data Preparation
Before diving into analysis, the dataset undergoes necessary preparations, such as:

- Identifying and handling missing values.
- Cleaning the data, including dropping irrelevant columns.
- Renaming columns for clarity.
- Converting the 'Date' column to the "datetime64" data type.
- Creating additional features like 'Year' and 'Month.'

# Exploratory Data Analysis
Exploratory Data Analysis (EDA) focuses on gaining insights into the data through visualizations and analytics. Key analyses include:

- Sales Distribution by Category: Identifying product categories contributing most to sales.
- Fulfillment and Shipment Analysis: Analyzing the impact of different fulfillment and shipment methods on sales.
- Top Selling Products: Determining the top-selling products based on quantity or revenue.
- Geographical Sales Distribution: Understanding how sales are distributed across different cities, states, and countries.

# Conclusion

1: Which product categories contribute the most to the sales in 2022?
The sales analysis for 2022 highlights the noteworthy contributions of various product categories. Notably, the 'Set' category emerges as the leading contributor to overall revenue, showcasing a substantial market presence. 'Blouse' and 'Dress' follow closely, underscoring their significance in the sales landscape. While 'Bottom,' 'Scarf,' and 'Top' also contribute, the preeminent position of 'Set,' 'Blouse,' and 'Dress' categories emphasizes their strategic importance in the sales portfolio.

2: How do different fulfillment methods and shipment types impact sales?
An examination of different fulfillment methods and shipment types reveals distinct patterns in sales impact. Sales with 'Amazon' fulfillment and 'Expedited' shipment type demonstrate a significant influence on the total revenue, underlining the effectiveness of this combination. Concurrently, 'Merchant' fulfillment, particularly when paired with 'Standard' shipment type, plays a role in revenue generation, albeit with a more measured impact.

3: What are the top-selling products in terms of quantity or revenue?
Delving into the top-selling products for 2022 unveils key performers driving both revenue and quantity metrics. Products such as 'J0230-SKD-M,' 'JNE3797-KR-L,' and 'JNE3797-KR-S' consistently emerge as frontrunners in terms of both sales and overall market demand. The sustained success of 'JNE3797-KR-L' and 'JNE3797-KR-S' underscores their resilience and popularity across diverse customer segments.

4: How are sales distributed across different cities, states, and countries?
Geographical analysis showcases a diverse distribution of sales across various cities, states, and regions. 'BENGALURU' in 'KARNATAKA' emerges as the top revenue-generating location, closely followed by 'HYDERABAD' in 'TELANGANA' and 'MUMBAI' in 'MAHARASHTRA.' This geographical distribution highlights the importance of tailoring marketing and distribution strategies to the unique dynamics of each location.

5: What is the distribution of order statuses (e.g., completed, canceled)?
The distribution of order statuses provides valuable insights into the efficiency of the order fulfillment process. The majority of orders fall under the 'Shipped' status, reflecting a robust and successful completion of transactions. 'Unshipped' orders constitute a smaller proportion, while 'Cancelled' orders remain a limited occurrence. These findings underscore the overall positive health of the order fulfillment process, with the vast majority of transactions successfully reaching completion.
