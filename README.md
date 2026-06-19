## House Price Prediction Using Machine Learning

# Project Overview

This project focuses on predicting house prices using Machine Learning techniques. The objective is to analyze various property features and build regression models that can estimate house prices accurately.

The project was completed as part of the Internship Week 1 Assignment and includes data preprocessing, exploratory data analysis, machine learning model development, evaluation, and visualization.

---

# Problem Statement

Real estate buyers and sellers often rely on manual estimates and market assumptions to determine property value. This project aims to develop a predictive model that estimates house prices based on property characteristics such as:

- Area
- Bedrooms
- Bathrooms
- Stories
- Parking
- Air Conditioning
- Furnishing Status
- Preferred Area
- Other amenities

---

# Dataset

Dataset Source:

Housing Prices Dataset (Kaggle)

The dataset contains:

- 545 records
- 13 features
- Target Variable: "price"

Features

Feature| Description
area| House area in square feet
bedrooms| Number of bedrooms
bathrooms| Number of bathrooms
stories| Number of floors
mainroad| Access to main road
guestroom| Availability of guest room
basement| Availability of basement
hotwaterheating| Hot water heating facility
airconditioning| Air conditioning facility
parking| Number of parking spaces
prefarea| Preferred area location
furnishingstatus| Furnishing condition
price| House selling price (Target)

---

# Tools Used

- Python 
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

# Project Workflow

1. Data Loading and Exploration

- Load Housing.csv
- Examine dataset structure
- Check data types
- Analyze missing values

2. Data Preprocessing

- Remove duplicate records
- Encode categorical variables
- Prepare features and target variable

3. Model Development

Linear Regression

A baseline regression model used for house price prediction.

Random Forest Regressor

An ensemble machine learning model used for improved prediction performance.

---

# Evaluation Metrics

The models were evaluated using:

MAE (Mean Absolute Error)

Measures average prediction error.

RMSE (Root Mean Squared Error)

Measures the magnitude of prediction errors.

R² Score

Indicates how well the model explains the variance in house prices.

---

# Visualizations

The project includes:

1. House Price Distribution Histogram

Displays the distribution of house prices.

2. Correlation Heatmap

Shows relationships among all variables.

3. Actual vs Predicted Scatter Plot

Compares model predictions with actual values.

---

# Key Findings

- Area is the most influential factor affecting house prices.
- Houses with more bathrooms generally have higher values.
- Parking facilities contribute positively to property prices.
- Air conditioning significantly increases property value.
- Preferred locations often command premium prices.

---

# Business Recommendations

Real estate businesses should prioritize:

- Larger properties
- Premium amenities
- Multiple bathrooms
- Adequate parking facilities
- Houses located in preferred areas

These factors consistently contribute to higher market prices and customer demand.

---

# Project Structure

HousePricePrediction

│── analysis.ipynb
│── Housing.csv
│── summary.docx
│
└── charts
    │── price_distribution.png
    │── correlation_heatmap.png
    │── actual_vs_predicted.png

# Future Improvements

- Hyperparameter tuning
- XGBoost Regressor implementation
- Feature selection optimization
- Deployment using Streamlit
- Real-time price prediction web application

---

# Author

Tanuj Kumar Singh

B.Tech CSE Student

Machine Learning & Data Science Enthusiast

---

# License

This project is created for educational and internship purposes only.
