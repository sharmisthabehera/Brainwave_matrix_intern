# Brainwave_matrix_intern
Created a SuperStore Sales Data Analysis by using Python.

# SUPER STORE SALES DATA ANALYSIS
## PROBLEM STATEMENT:

The SuperStore chain has accumulated a wealth of sales data across various customer segments, products, and regions. Despite its success, the company faces challenges in maximizing its profitability, customer retention, and market penetration. With competition intensifying, it is crucial for SuperStore to gain a deeper understanding of its sales trends, customer behavior, and product performance.

The objective is to analyze the SuperStore dataset to uncover actionable insights that can drive strategic decision-making. The analysis aims to address the following key business questions: 
i) Customer Segmentation and Loyalty
ii) Sales Performance and Product Analysis
iii) Trend Analysis and Market Insights
iv) Segment-Specific Strategies 

## DESCRIPTION:

The SuperStore Sales dataset is a comprehensive collection of transactional data from a retail store chain, capturing a wide array of information related to sales, customers, products, and geographical distribution. The dataset is structured with various features that allow for in-depth analysis of sales trends, customer behavior, product performance, and regional sales patterns.

## DATASET INFORMATION:

The dataset contains 9,800 rows and 18 columns. These columns include various attributes such as 'Row ID', 'Order ID', 'Order Date', 'Ship Date', 'Ship Mode', 'Customer ID', 'Customer Name', 'Segment', 'Country', 'City', 'State', 'Postal Code', 'Region', 'Product ID', 'Category', 'Sub-Category', 'Product Name', and 'Sales'. The 'Postal Code' column had some missing values (11 in total), which were filled with 0. The data type of this column was then converted from float to int. The dataset has been downloaded from kaggle.

## PROJECT STRUCTURE:

Data Preprocessing: The dataset is loaded, and the 'Order Date' column is converted to a datetime format. Data is grouped by different periods (e.g., monthly, quarterly, yearly) to analyze sales trends.

Data Visualization: Pie charts, bar plots, and line charts has been plotted for sales trends over time, including monthly, quarterly, and yearly trends.

## OBSERVATIONS:

A line plot shows how sales have changed year over year. Peaks or valleys in the graph indicate periods of higher or lower sales. Specific years may show a significant increase or decrease in sales, which could be correlated with external factors like market conditions, product launches, or promotional activities.

## RESULTS:

i) Missing values were found in the Postal Code column (11 missing values), which were filled with 0. The Postal Code column was then converted to int64.
ii) The analysis identified the most frequent customers, with William Brown (Consumer segment) placing 35 orders and Paul Prost (Home Office segment) placing 34 orders. This indicates a strong loyalty within these segments.
iii) High sales were observed for products like "Bush Somerset Collection Bookcase" and "Hon Deluxe Fabric Upholstered Stacking Chairs," indicating their popularity and significant contribution to overall revenue.
iv) Different customer segments (Consumer, Corporate, Home Office) showed varying engagement levels. The Consumer segment, in particular, had the highest order frequencies, indicating a potentially loyal customer base in this segment.

## CONCLUSIONS:

The analysis provided in this notebook effectively demonstrates how to track and visualize yearly sales trends using historical data. By converting the order dates to a yearly period and grouping the data accordingly, the total sales for each year are calculated and plotted. This approach allows for a clear understanding of how sales have evolved over time, which can be crucial for making informed business decisions, identifying growth patterns, or spotting potential issues in sales performance. The visualizations generated provide an intuitive and immediate understanding of the trends, making it easier to communicate findings to stakeholders.

## CONTACT INFORMATION:

For any inquiries or feedback regarding this project, please contact:

Linkedin: https://www.linkedin.com/in/sharmistha-behera-b704581b6
Email: sharmisthabehera56@gmail.com
