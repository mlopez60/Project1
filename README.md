# Project1

Amazon Sales Analysis

Team Members: Mitchell Fairgrieve & Matthew Lopez

Project Description: Analyzing Amazon India products, ratings, and reviews.

Research Questions:
What is the sales breakdown by Product Category?
How does price affect ratings/reviews? discounted-price?
What is the correlation between length of reviews vs rating?

Dataset: https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset

Tasks:
Organizing data (locate missing values/NaN values)
Cleaning data (identify relationships)
Visualizing data (at least two per question)
Analyzing data
Our findings (prepare presentation)


Column names: {product_id, product_name,	category, discounted_price, actual_price,	discount_percentage,	rating,	rating_count, about_product,	user_id, user_name,	review_id,	review_title, review_content,	img_link, product_link}


What is the sales breakdown by Product Category?
Needed columns:product_id, product_name, category, rating, rating_count, actual_price, discount_percentage

How does price affect ratings/reviews? Discounted-price?
Needed columns:product_id, product_name, rating, rating_count, actual_price, discounted_price, discount_percentage, review_id,review_title, review_content

What is the correlation between length of reviews vs rating?
Needed columns:product_id, product_name, rating, rating_count, review_id,review_title, review_content
length of reviews = len(review_content)
