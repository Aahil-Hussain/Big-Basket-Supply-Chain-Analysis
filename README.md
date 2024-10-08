# Big-Basket-Supply-Chain-Analysis

# Project Overview
This project involves analyzing the sales of various products on Big Basket and building a predictive model to forecast sales prices based on various features such as product category, brand, and discounts.
The primary goal of this project is to perform comprehensive data analysis on Big Basket's product data and develop a model that predicts the sale prices of products. This analysis can provide insights into pricing strategies, customer preferences, and discount effectiveness.

# Dataset
The dataset contains the following columns:

- product: The name of the product.
- category: The main category to which the product belongs.
- sub_category: The sub-category of the product.
- brand: The brand of the product.
- sale_price: The final price at which the product is sold.
- market_price: The market price of the product.
- type: The type of the product (e.g., grocery, electronics, etc.).
- rating: The customer rating for the product.
- description: A brief description of the product.
- discounts: The percentage or amount of discounts applied.

# Objective
- Data Analysis: Perform detailed exploratory data analysis (EDA) to uncover trends, patterns, and correlations between product features such as discounts, categories, and brands.
- Price Prediction Model: Build a machine learning model to predict the sale price of products based on features such as brand, market price, discounts, and ratings.
- Insights Generation: Derive insights regarding customer behavior, discount strategies, and the effect of ratings on sales.

# Analysis and Visualizations
- Various charts were used to analyze relationships between categories, brands, and their respective sales performance. Visualizations include:
- Bar charts for comparing average sale prices across categories and brands.
- Scatter plots to examine the relationship between discounts and sale price.
- Heatmaps to identify correlations between features like market price, sale price, and ratings.
- Box plots for showing the distribution of sale prices across different product types.

# Model Performance
## A Linear Regression model was built to predict the sale price based on the features provided in the dataset.
- R² Score: 0.92
- This indicates that the model explains 92% of the variance in sale prices, making it a highly accurate predictor for pricing strategies.

# Conclusion
- The Linear Regression model achieved a high R² score of 0.92, showing that it can accurately predict product sale prices based on attributes like market price, discount, and brand.
- From the analysis, it was observed that discounts and higher ratings tend to drive sales, while products from premium brands often have less deviation in their sale prices compared to their market prices.
- The analysis provides valuable insights for pricing and discount strategies, helping Big Basket optimize its sales performance.

- Experiment with more advanced machine learning models like Random Forest or Gradient Boosting to see if further improvements can be made in price prediction.
