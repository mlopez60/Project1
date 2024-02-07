# Project1

Amazon Sales Analysis

Team Members: Mitchell Fairgrieve & Matthew Lopez

Project Description: Analyzing Amazon India products, ratings, and reviews.

Research Questions:
What is the sales breakdown by Product Category?
How does price affect ratings/reviews? discounted-price?
What is the correlation between length of reviews vs rating?



Dataset: https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset

Data Limitations: 

Data set seems to be too specific in terms of products pulled:
 
Majority of products from only 3 categories

Majority of products with only high reviews



Tasks:
Organizing data (locate missing values/NaN values)
Cleaning data (identify relationships)
Visualizing data (at least two per question)
Analyzing data
Our findings (prepare presentation)


Data Breakdown:

Column names: {product_id, product_name,	category, discounted_price, actual_price,	discount_percentage,	rating,	rating_count, about_product,	user_id, user_name,	review_id,	review_title, review_content,	img_link, product_link}


What is the sales breakdown by Product Category?
Needed columns:product_id, product_name, category, rating, rating_count, actual_price, discount_percentage

How does price affect ratings/reviews? Discounted-price?
Needed columns:product_id, product_name, rating, rating_count, actual_price, discounted_price, discount_percentage, review_id,review_title, review_content

What is the correlation between length of reviews vs rating?
Needed columns:product_id, product_name, rating, rating_count, review_id,review_title, review_content
length of reviews = len(review_content)


Process: 
Imported CSV data from data set found on Kaggle

Cleaned up data, dropped NA rows,  fixed formats, and converted currencies

Created various DataFrames for our analysis

Created visuals such as bar charts, pie charts, scatter plots. 

Performed regression analysis and Pearson’s R test.



Summary: 
Question 1: Initially, we had 9 major categories, however we found our data focuses on 3 main categories (Electronics, Computers&Accessories, & Home&Kitchen). Based off our sample, there is little to no correlation between the categories and any of these tested factors.

Question 2: For our sample set, we found that none of our factors have any significant correlation between the set factors.

Question 3: Based off of Pearson’s R, we rejected the Null Hypothesis. There appears to be some sort of relationship between length of review and average rating for a product. However, the relationship goes against our alternative still. 



Future Ideas: 

Larger sample size

Perform different statistical tests

Compare to different data sets

Perform our own web scraping for data

