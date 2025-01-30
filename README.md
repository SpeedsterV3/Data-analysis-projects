Project Summary:

In this project, various data cleaning, machine learning preprocessing, and data visualization techniques were applied to a dataset of Amazon products. The objective was to clean, preprocess, and visualize the data to gain insights into product ratings, pricing, and categories. Here's a breakdown of the tools and techniques used:

Data Cleaning and Preprocessing:

Pandas: This powerful library was used for data manipulation and cleaning. We used it to load the dataset, remove currency symbols from price columns, and handle missing values in the ratings column.
Scikit-learn: The LabelEncoder from Scikit-learn was applied to encode categorical variables (like product categories) into numerical values to make the dataset ready for machine learning models.
Data Visualization:

Seaborn & Matplotlib: These libraries were used for visualizing the relationships and distributions in the dataset. Specifically:
Heatmap: A correlation heatmap was created to visualize the relationships between numeric variables such as discounted_price, actual_price, and rating.
Histogram: A histogram was plotted to analyze the distribution of ratings, providing insights into the overall ratings distribution of products.
Box Plot: A box plot was used to examine the distribution of discounted prices across different product categories.
Machine Learning Preparation:

While the current project focuses on data cleaning and visualization, the preprocessing steps performed (such as encoding categorical features and handling missing values) would enable the dataset to be ready for future machine learning tasks, such as predicting product ratings or pricing strategies.
Tools Used:
Pandas for data manipulation and cleaning
Scikit-learn for encoding categorical variables
Seaborn and Matplotlib for data visualization (heatmap, histogram, and box plot)
This project demonstrates the initial steps of preparing data for further analysis or machine learning tasks, while also offering valuable visual insights into the dataset’s structure and relationships.

About Dataset
This dataset is having the data of 1K+ Amazon Product's Ratings and Reviews as per their details listed on the official website of Amazon

Features

product_id - Product ID
product_name - Name of the Product
category - Category of the Product
discounted_price - Discounted Price of the Product
actual_price - Actual Price of the Product
discount_percentage - Percentage of Discount for the Product
rating - Rating of the Product
rating_count - Number of people who voted for the Amazon rating
about_product - Description about the Product
user_id - ID of the user who wrote review for the Product
user_name - Name of the user who wrote review for the Product
review_id - ID of the user review
review_title - Short review
review_content - Long review
img_link - Image Link of the Product
product_link - Official Website Link of the Product
Inspiration

Amazon is an American Tech Multi-National Company whose business interests include E-commerce, where they buy and store the inventory, and take care of everything from shipping and pricing to customer service and returns. I've created this dataset so that people can play with this dataset and do a lot of things as mentioned below

Dataset Walkthrough
Understanding Dataset Hierarchy
Data Preprocessing
Exploratory Data Analysis
Data Visualization
Making Recommendation System
This is a list of some of that things that you can do on this dataset. It's not definitely limited to the one that is mentioned there but a lot more other things can also be done.
