# Amazon-products-and-Kultra-Mega-Stores-Inventory-products-Review-DSA-project-
## PROJECT TOPIC
-AMAZON PRODUCT REVIEW ANALYSIS
### PROJECT OVERVIEW
-This project work focused on rating, discounting and reviewing of Amazon products sold by Realtechinsights. -The company provides e-commerce analytics solutions to sellers on platforms.
#### OBJECTIVES
The primary objective of this study is to perform an in-depth exploratory data analysis (EDA) on Amazon product listings to uncover meaningful insights into product performance, customer behavior, and pricing strategies. Specifically, the study aims to:

* Assess the impact of discount percentages across various product categories to understand pricing trends and promotional effectiveness.

* Analyze product availability and distribution by category to determine product listing density and market saturation.

* Evaluate customer engagement by measuring review volume, average ratings, and rating distributions across categories.

* Identify high-performing products based on user reviews and ratings, and examine their pricing and discount structures.

* Compare actual vs discounted prices to understand pricing strategies and their potential influence on consumer perception.

* Estimate potential revenue using product pricing and customer review metrics to assess category profitability.

* Categorize products by price range to explore pricing diversity and customer targeting within the product catalog.

This analysis will provide data-driven insights to inform strategic decisions regarding inventory management, marketing campaigns, product pricing, and customer satisfaction enhancement on the Amazon platform
##### DATA SOURCE
Dataset extracted from Amazon product listings provided Excel file)

It contains a collection of Amazon products such as customer user_id, product items, username, rating and customer review.


###### DATA TOOL

* Microsoft excel
* Excel power query
* Excel pivot table
* Excel pivot chat for visualisation
###### DATA CLEANING AND PREPARATION
The dataset went through cleaning and transformation to get accuracy such as;

* Filtering the irrelevant data and duplicates.
* Text cleaning
* Removing irrelevant colums
* Creating additional column

  ###### EXPLORATORY DATA ANALYSIS(EDA)

  The Exploratory Data Analysis (EDA) phase was conducted to uncover hidden patterns, summarize key characteristics, and extract meaningful insights from the Amazon product dataset. The analysis focused on product performance, customer behavior, pricing strategies, and category-level comparisons.

###### 1. Category Distribution
Products were spread across multiple categories such as Electronics, Computers & Accessories, Home & Kitchen, etc.

The highest number of products was observed in Computers & Accessories and Electronics, indicating high competition and diversity in those categories.

###### 2. Discount Patterns
Categories like Home Improvement and Computers & Accessories offered the highest average discounts, often exceeding 50%.

A considerable number of products had discounts of 50% or more, especially in categories with heavy retail competition.

###### 3. Rating Analysis
Products showed an overall average rating between 3.5 and 4.5, with a few top-rated products achieving perfect 5.0 ratings.

A rating distribution analysis (rounded to nearest integer) revealed most products were rated 4.0, followed by 3.0 and 5.0, showing a skew towards positive customer experiences.

###### 4. Customer Engagement
Review volume varied significantly across products. Some products had over 1,000 reviews, while many had fewer than 10.

Products with the highest number of reviews tended to have mid-range prices and strong customer ratings, indicating quality and affordability drive engagement.

###### 5. Price Comparison
The average actual prices were consistently higher than discounted prices, as expected.

The gap between actual and discounted prices was largest in categories with higher discount percentages, confirming aggressive promotional strategies.

###### 6. Revenue Estimation
A new field potential_revenue was calculated using actual_price × rating_count.

Categories like Electronics and Health & Personal Care showed the highest revenue potential, driven by high unit prices and strong review counts.

###### 7. Price Range Distribution
Products were bucketed into:

< ₹200

₹200 – ₹500

> ₹500

Most products were found in the ₹200 – ₹500 range, indicating mid-range pricing is common on the platform.

###### 8. Top Products Identification
Products with the highest average ratings and most reviews were listed to help identify potential star performers and customer favorites.

