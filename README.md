# Oasis-Infobyte-Data-Science-Internship
Data Science Internship Projects - Oasis Infobyte
# Car Price Prediction Using Machine Learning

## Project Overview

This project focuses on predicting the selling price of used cars using Machine Learning. A Linear Regression model was developed to estimate car prices based on important features such as manufacturing year, present price, and kilometers driven.

The objective of this project is to understand regression modeling, feature selection, data preprocessing, and performance evaluation using real-world data.

## Dataset Information

The dataset includes the following features:

- Car_Name
- Year
- Selling_Price (Target Variable)
- Present_Price
- Driven_kms
- Fuel_Type
- Selling_type
- Transmission
- Owner

For prediction, the following features were selected:

- Year
- Present_Price
- Driven_kms

Target Variable:
- Selling_Price

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Project Workflow

1. Data Loading  
   The dataset was loaded using Pandas.

2. Data Preprocessing  
   - Checked for missing values  
   - Cleaned column names  
   - Selected relevant features  

3. Feature Selection  
   Selected numerical features for prediction:
   - Year  
   - Present_Price  
   - Driven_kms  

4. Train-Test Split  
   - 80% training data  
   - 20% testing data  

5. Model Training  
   A Linear Regression model was trained on the training dataset.

6. Model Evaluation  

   R² Score Achieved: 0.8257  

## Model Performance

The model achieved an R² score of 0.82, indicating strong predictive performance. The model explains approximately 82% of the variance in car selling prices.

## Conclusion

A Car Price Prediction model was successfully built using Linear Regression. The model demonstrates strong accuracy and effectively estimates car prices based on selected features.

## Author

Vaibhav
