# Amazon-products-Review-DSA-project-
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

##### 📊 Dataset Overview
- Total Records: 1,462
- Fields: 16
- Source: DSA Canvas LMS
- Contains:
    - Product details (Name, Category, Price, Discounts)
    - User engagement metrics (Review count, Ratings)
    - Price variations and Revenue potential

##### 📈 Key Metrics (KPIs)
| Metric                                | Value             |
|---------------------------------------|-------------------|
| ⭐ Average Rating                      | 4.10              |
| 🗣️ Total Reviews                      | 1,462             |
| 🔖 Average Discount %                 | 48%               |
| 💰 Average Actual Price               | ₹5,453.09         |
| 💸 Average Discounted Price           | ₹3,129.98         |
| 💵 Total Actual Revenue Potential     | ₹121.3 Billion    |
| 🧾 Total Discounted Revenue           | ₹71.9 Billion     |
| 📉 Discount Impact on Revenue         | ₹49.4 Billion     |


###### 🛠 DATA TOOL

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

#### Visualization 
<img width="1368" height="729" alt="visualization" src="https://github.com/user-attachments/assets/77069745-79c8-4c53-9768-5ba55f1a202e" />

Based on the visualized data from the dashboard, here is a comprehensive analysis and summary covering all key metrics and insights:

###### 1. Review and Rating Overview:
Average Rating: 4.10 out of 5, indicating generally positive customer feedback.
Total Reviews: The total review count suggests a significant level of customer engagement.
Average Discount Percentage: 48%, which may influence customer purchasing decisions and review trends.
Actual Price vs. Discounted Price: The average actual price is approximately $5453.09, with discounted prices around $3129.98, reflecting substantial price reductions.
###### 2. Product and Category Analysis:
Product Count in Each Category: The dashboard provides a breakdown of product distribution across categories.
Highest Rated Products: The pie chart highlights the product categories or individual products with the highest customer ratings.
Total Number of Reviews by Category: Shows which categories or products have the most feedback, helping identify popular items.
###### 3. Review Distribution and Trends:
Review Distribution Over Product Count: Most products have a specific review count, with a notable peak indicating a common review volume.
Products With Less Than 1000 Reviews: Identifies products with lower review counts, possibly newer or less popular items.
Rating Distribution: The bar chart highlights how reviews are spread across rating levels, with likely a concentration around 4-5 stars.
###### 4. Discount and Revenue Insights:
Percentage Discount Greater Than 50%: Trends indicate how many products are heavily discounted, potentially driving sales.
Revenue Potential by Category: The data suggest will show which categories generate the highest revenue potential, useful for targeted marketing.
Highest Discounted Products: Identifies products with the most significant discounts, likely to attract more buyers.
###### 5. Price Range and Revenue:
The product count by price range offers insights into customer price sensitivity.
The overall revenue potentials suggest which products or categories could be prioritized.
###### 6. Additional Observations:
Trends over time or categories show shifts in review dynamics and discount strategies.
The dashboard appears designed to assist decision-making around pricing, marketing, and inventory planning based on review data.

### 📬 Contact
If you have questions or would like to collaborate:    

Udo Ikontiense Nathaniel 


📧 Email: [ikontienseudo@gmail.com]

