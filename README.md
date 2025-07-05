# DSA Project Documentation

This project is part of a capstone case study from the **DSA Data Analysis Program**, aimed at analyzing product and customer review data scraped from Amazon to generate insights that can support product improvement, marketing strategies, and customer engagement.

## Project Topic: E-Commerce Product Insights | Strategic Analysis of Amazon Listings

### Project Overview

This data analysis project focuses on uncovering product and customer engagement insights from an Amazon-based e-commerce dataset. The goal was to explore key indicators that influence product performance, customer preferences, and strategic pricing.

By examining multiple data points—including product categories, pricing, discounts, customer reviews, and ratings—I was able to draw meaningful insights that support data-driven storytelling and decision-making. The analysis revealed trends in customer behavior, product visibility, and potential revenue, ultimately guiding recommendations for better marketing focus and product optimization.

This project also highlights the practical application of Microsoft Excel tools such as pivot tables, calculated columns, and dynamic dashboards in building a clear, interactive summary of insights.

### Data Sources

The primary dataset used in this analysis is the Amazon Case Study Excel Worksheet, obtained from the Learning Management System (LMS) of the DSA Data Analysis Program, under the Capstone Project Files.

### Tools Used

- Microsoft Excel [Download here](https://www.microsoft.com)
    - Used for data cleaning, transformation, and analysis through pivot tables, calculated columns, and formulas. Also employed to build an interactive dashboard for visualizing insights.
- GitHub [Download here](https://github.com)
    - Utilized for version control and to host the project as part of a professional portfolio.
 
### Data Cleaning and Preparation

At the initial stage of data cleaning and preparation, the following key steps were carried out to ensure the dataset was structured and ready for analysis:

- Removed duplicate product entries
- Checked and handled missing values in price, rating, and review fields
- Converted actual price, discounted price, discount percentage, rating, and rating count to numeric formats
- Trimmed extra spaces and standardized text formatting in product and category columns
- Cleaned special characters and links from review content fields
- Recalculated and verified discount percentages from price fields
- Categorized products into price range buckets for segmentation
- Confirmed uniqueness of product IDs to maintain data integrity
- Split or prepared comma-separated review-related fields for further analysis if needed

### Exploratory Data Analysis

Key questions explored during the analysis:

- What is the average discount percentage by product category? 
- How many products are listed under each category? 
- What is the total number of reviews per category?  
- Which products have the highest average ratings? 
- What is the average actual price vs the discounted price by category? 
- Which products have the highest number of reviews? 
- How many products have a discount of 50% or more? 
- What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)? 
- What is the total potential revenue (actual_price × rating_count) by category? 
- What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)?
- How does the rating relate to the level of discount? 
- How many products have fewer than 1,000 reviews? 
- Which categories have products with the highest discounts? 
- Identify the top 5 products in terms of rating and number of reviews combined.
    
### Data Analysis

``` Excel

=


