# Reat Estate Price Prediction

###  Overview

This project involves analyzing and predicting real estate prices using a dataset containing information about properties. The goal is to provide insights into key features influencing property prices and to build an accurate predictive model to assist real estate professionals in making data-driven decisions.

### Dataset

The dataset used in this project contains the following features:

- SquareFeet: Size of the house in square feet.
- Bedrooms: Number of bedrooms in the house.
- Bathrooms: Number of bathrooms in the house.
- Neighborhood: Type of neighborhood (Rural, Suburb, Urban).
- YearBuilt: Year the house was built.
- Price: The sale price of the house (target variable).

### Features

1. Data Exploration and Cleaning
2. Feature Engineering and Transformation
3. Price Prediction using Machine Learning
4. Model Evaluation and Insights
5. Correlation Analysis and Feature Importance

### Key Insights

- The correlation analysis reveals that square footage has the strongest relationship with property prices.
- Log-transformed price (LogPrice) allows for more stable and less skewed predictions.
- The Random Forest Regressor model achieves an R² score of approximately 0.50, suggesting room for improvement in model accuracy.

### Visualizations

- Scatter plots to show the relationship between SquareFeet and Price by Neighborhood.
- Box plots to visualize outliers in numerical columns.
- Correlation heatmap to explore the relationships between numerical features.
- Bar plots for average house prices by neighborhood.
- Feature importance chart from Random Forest model.
