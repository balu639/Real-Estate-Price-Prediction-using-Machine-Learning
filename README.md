# Real Estate Price Prediction Project

## Introduction
This project aims to predict real estate prices in Bengaluru using machine learning techniques. The dataset used is the Bengaluru house price dataset from Kaggle.

## Data Preprocessing
- Removed unimportant features: 'area_type', 'availability', 'society', 'balcony'.
- Checked for NA values and removed them.
- Converted all numerical values to floats.
- Added 'price_per_sqft' feature for deeper analysis.

## Outlier Detection and Removal
- Detected outliers based on 'price_per_sqft'.
- Removed outliers to ensure model accuracy.

## Model Selection and Evaluation
- Utilized GridSearchCV to test Linear Regression, Lasso, and Decision Tree models.
- Identified Linear Regression as the best performer due to its superior performance.

## Prediction
- Conducted predictions using the trained Linear Regression model.

## Web Application Development
- Developed a user-friendly web interface using HTML, JavaScript, and CSS.
- Implemented the server-side logic using AWS, Flask, and Python.

## Conclusion
Through meticulous preprocessing, outlier detection, and model evaluation, the Real Estate Price Prediction project successfully determined Linear Regression as the optimal model. The web application provides a seamless interface for users to predict housing prices accurately.
