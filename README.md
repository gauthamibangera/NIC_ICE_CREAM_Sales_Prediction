# NIC Ice Cream Sales Prediction

## 1. Project Overview

This project analyzes ice cream sales patterns and develops a Linear Regression model to predict sales revenue in INR. It explores the relationship between sales and factors such as temperature, footfall, discounts, and product categories.

*Disclaimer: The analysis uses a simulated dataset of 3,000 records for educational purposes. It does not represent actual NIC Ice Creams sales data.*

## 2. Objectives

- Analyze sales trends across product categories and temperature ranges.
- Explore relationships between discounts, footfall, and sales.
- Clean and preprocess data for analysis and modeling.
- Build and evaluate a sales prediction model using Linear Regression.

## 3. Dataset

- **Records:** 3,000
- **Target Variable:** `Sales_INR`
- **Key Features:** Temperature, footfall, discounts, product category, weather, and advertising spend.

## 4. Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## 5. Key Insights and Results

- Average sales were higher in hotter temperature ranges in the simulated dataset.
- Super Premium recorded the highest average sales among the product categories analyzed.
- **Model:** Linear Regression
- **R² Score:** 0.51
- **Mean Absolute Error (MAE):** Approximately ₹2,188

## 6. Conclusion

The analysis identified patterns in sales across temperature ranges and product categories. The Linear Regression model explained approximately 51% of the variation in test-set sales, providing a baseline for further experimentation with features and alternative regression algorithms.
