# Housing-Market

###  Overview

The primary objective of this project is to predict the price of a house using its features. This project explores data cleaning, preprocessing, and regression models including Linear Regression, Decision Tree Regression, and Random Forest Regression. We also perform data visualization, outlier detection, and feature importance analysis to understand the relationship between features and house prices.

### Dataset

The dataset used in this project contains the following features:

- SquareFeet: Size of the house in square feet.
- Bedrooms: Number of bedrooms in the house.
- Bathrooms: Number of bathrooms in the house.
- Neighborhood: Type of neighborhood (Rural, Suburb, Urban).
- YearBuilt: Year the house was built.
- Price: The sale price of the house (target variable).

### Project Steps
1. Data Preprocessing
- Unzipped the dataset and loaded the CSV into a DataFrame.
- Checked for missing values and duplicate rows.
- Filtered out any negative values in the "Price" column.

2. Exploratory Data Analysis (EDA)
- Performed initial data exploration by viewing basic statistics and data types.
- Visualized relationships between house prices and features using scatter plots, box plots, and bar charts.
- Analyzed the distribution of house prices and square footage.
- Detected and visualized outliers in key columns like Price, SquareFeet, and YearBuilt.

3. Feature Engineering

- One-hot encoded the categorical feature Neighborhood to prepare it for regression models.
- Scaled the numerical features using StandardScaler for consistency and model performance.

4. Model Building and Evaluation

- Split the dataset into training and testing sets (80% training, 20% testing).
- Trained multiple regression models: Linear Regression, Decision Tree Regression, Random Forest Regression
- Evaluated the models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R2 score.

5. Cross-Validation and Feature Importance

- Used cross-validation to evaluate model performance and reduce overfitting.
- Analyzed feature importance, especially for the Random Forest model, to understand which features have the most significant impact on house prices.

6. Model Saving

- Saved the trained Random Forest model using joblib for future use.

### Results

The project successfully trained three regression models and compared their performances:

- Linear Regression: Provided a baseline for price predictions.
- Decision Tree Regression: Showed non-linear patterns but may have overfitted.
- Random Forest Regression: Performed the best with higher R2 scores and lower error metrics.

### Visualizations

- Scatter plots to show the relationship between SquareFeet and Price by Neighborhood.
- Box plots to visualize outliers in numerical columns.
- Correlation heatmap to explore the relationships between numerical features.
- Bar plots for average house prices by neighborhood.
- Feature importance chart from Random Forest model.
