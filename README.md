# Reat Estate Price Prediction

###  Overview

This project involves analyzing and predicting real estate prices using a synthetic dataset containing information about properties. The goal is to provide insights into key features influencing property prices and to build an accurate predictive model to assist real estate professionals in making data-driven decisions.

The project leverages advanced machine learning techniques, including Random Forest, Gradient Boosting, and XGBoost, to predict housing prices. The best-performing model achieves an R² score of 0.56, demonstrating strong predictive accuracy.

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

- SquareFeet and HomeAge are the most important features influencing property prices.
- The log transformation of the target variable (Price) improved model stability and performance.
- Gradient Boosting outperformed Random Forest and XGBoost, demonstrating its effectiveness for this regression task.
- The performance metrics indicate that Gradient Boosting is the best model for this dataset, but there is still room for improvement. By refining the model and exploring additional features, you can achieve even better results.

### Visualizations

- Scatter plots to show the relationship between SquareFeet and Price by Neighborhood.
- Box plots to visualize outliers in numerical columns.
- Correlation heatmap to explore the relationships between numerical features.
- Bar plots for average house prices by neighborhood.
- Feature importance chart from Random Forest model.

### Future Work

- Hyperparameter Tuning: Use GridSearchCV or RandomizedSearchCV to fine-tune the best-performing model (Gradient Boosting).
- Advanced Feature Engineering: Explore interactions between features or incorporate external data (e.g., local amenities, school ratings).
- Error Analysis: Investigate large prediction errors to identify patterns and improve the model.
- Deployment: Deploy the model as a web application using Flask or Streamlit for real-time price predictions.

### Source

Dataset: [Housing Price Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/muhammadbinimran/housing-price-prediction-data)
