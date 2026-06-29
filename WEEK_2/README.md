# Week 2: Tesla Deliveries Analysis & Forecasting

## Overview

This project analyzes Tesla's monthly vehicle delivery data (2015–2025) to uncover business insights, build predictive machine learning models, and forecast future deliveries using time series analysis.

The notebook follows a complete end-to-end data science workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, regression modeling, hyperparameter tuning, and forecasting.

---

## Objectives

- Analyze historical Tesla delivery trends.
- Explore relationships between production, pricing, and deliveries.
- Engineer meaningful features for predictive modeling.
- Compare multiple machine learning regression models.
- Forecast future deliveries using Prophet.
- Generate business insights and recommendations.

---

## Dataset

**File:** `tesla_deliveries_dataset_2015_2025.csv`

The dataset contains monthly Tesla vehicle delivery information, including:

- Date
- Region
- Model
- Production Units
- Estimated Deliveries
- Average Price
- Battery Capacity
- Range
- Inventory Levels
- Source Type

---

## Workflow

### 1. Data Understanding
- Loaded dataset
- Examined dataset structure
- Statistical summary
- Checked missing values and duplicates

### 2. Data Cleaning
- Removed duplicate records
- Handled missing values
- Converted data types where required

### 3. Feature Engineering
Created additional features including:
- Year
- Month
- Vehicle Segment
- Production-to-Delivery Ratio
- Estimated Revenue
- Delivery Lag (Lag-1)
- 3-Month Rolling Mean

### 4. Exploratory Data Analysis (EDA)
Visualizations include:
- Deliveries by Model across Regions
- Monthly Delivery Trend
- Correlation Heatmap
- Production vs Estimated Deliveries
- Feature Importance

### 5. Feature Selection
- Selected relevant predictor variables
- Defined target variable
- Prepared feature matrix for modeling

### 6. Model Development
Implemented:
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

Evaluation Metrics:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 7. Model Validation
- 5-Fold Cross Validation
- Performance Comparison

### 8. Hyperparameter Tuning
Optimized the Random Forest model using GridSearchCV.

### 9. Time Series Analysis
Performed:
- Augmented Dickey-Fuller (ADF) Stationarity Test
- Prophet Forecasting
- 12-Month Future Delivery Forecast

### 10. Business Insights
Generated business recommendations based on model findings and forecasting results.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Prophet
- Statsmodels

---

## Key Outcomes

- Developed multiple regression models for delivery prediction.
- Compared model performance using standard evaluation metrics.
- Identified the most influential features affecting vehicle deliveries.
- Forecasted Tesla's future monthly deliveries using Prophet.
- Derived actionable business recommendations from analytical insights.

---

## Repository Structure

```
Week-2/
│── week2_Mahima_Vahadne.ipynb
│── tesla_deliveries_dataset_2015_2025.csv
└── README.md
```

---

## Learning Outcomes

This project strengthened practical understanding of:

- Data preprocessing and feature engineering
- Exploratory Data Analysis (EDA)
- Regression modeling
- Cross Validation
- Hyperparameter tuning
- Feature importance analysis
- Time series forecasting
- Business-driven interpretation of machine learning results

---

**Author:** Mahima Vahadne  
**Internship:** Celebal Technologies – Data Science Internship
