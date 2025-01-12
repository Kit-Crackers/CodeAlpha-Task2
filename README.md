# Car Price Prediction with Machine Learning

## Overview
The project aims to predict the selling price of cars based on various factors such as the car's brand, features, horsepower, mileage, and other attributes. By leveraging machine learning, the model provides insights into how different features affect car prices, making it useful for buyers and sellers in the automotive industry.

## Objective
To develop a machine learning model that accurately predicts car prices using relevant features from a given dataset.

## Dataset Used
The dataset contains the following columns:
- **Car_Name**: Name of the car
- **Year**: Year of manufacture
- **Selling_Price**: Price at which the car is being sold
- **Present_Price**: Current ex-showroom price of the car
- **Driven_kms**: Distance driven in kilometers
- **Fuel_Type**: Type of fuel used (e.g., Petrol, Diesel, CNG)
- **Selling_type**: Type of seller (e.g., Dealer, Individual)
- **Transmission**: Transmission type (e.g., Manual, Automatic)
- **Owner**: Number of previous owners

## Results
The Random Forest Regressor model achieved a high accuracy in predicting car prices. The evaluation metrics include:
- **Mean Absolute Error (MAE)**: Provides the average absolute difference between predicted and actual values.
- **Mean Squared Error (MSE)**: Measures the average squared difference between predicted and actual values.
- **R-squared Score**: Indicates how well the model explains the variance in the target variable.

### Visualization
- **Feature Importance**: Highlights the impact of each feature on car prices.
- **Correlation Heatmap**: Visualizes the relationships between numerical features.

## Conclusion
The project successfully demonstrates how machine learning can be used to predict car prices based on various features. The model's performance indicates its reliability in capturing the complex relationships between car attributes and their selling prices. This approach can assist stakeholders in making informed decisions in the car resale market.

