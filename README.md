**Gold Price Prediction Model using Machine Learning**

This project is a Machine Learning-based Gold Price Prediction System developed using Python and Random Forest Regression.
The model predicts the future price of Gold (GLD index value) based on financial indicators.

**Project Overview**

Gold is one of the most important investment assets, and its price depends on multiple market factors.
This project analyzes a historical Gold dataset and builds a predictive model using regression techniques.

**The workflow includes:**

Data loading

Exploratory analysis

Correlation study

Train-test split

Model training

Evaluation and prediction

Machine Learning Algorithm Used
Random Forest Regressor

Ensemble-based algorithm

Works by creating multiple decision trees

Reduces overfitting and improves prediction stability

Ideal for numerical prediction tasks

**Dataset Details**

Source: Gold Price Historical Dataset

Target Variable: GLD (Gold Price Index)

Other Market Features Used:

SPX (S&P 500 Index)

USO (Oil Price)

SLV (Silver Price)

EUR/USD (Currency Exchange Rate)

Date column was removed from features

**Technologies & Libraries**

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook / Google Colab

**Project Workflow**
1. Data Collection

Loaded the CSV dataset into a pandas DataFrame.

2. Data Analysis

Checked dataset shape

Verified datatypes

Confirmed that no missing values exist

3. Exploratory Data Visualization

Generated correlation heatmap

Observed strong positive correlation between GLD and Silver (SLV)

4. Feature Engineering

Removed the Date column

Split data into:

Features (SPX, USO, SLV, EUR/USD)

Target (GLD)

5. Train–Test Split

80% training

20% testing

Random state for reproducibility

6. Model Training

Random Forest Regressor trained on training data

7. Model Evaluation

Tested on unseen test data

Performance evaluated using R² Score

**Model Performance**

R² Score: ~0.98 – 0.99

Indicates excellent predictive accuracy

Visual comparison shows actual values closely matching predictions

Prediction System

The trained model is able to:

Predict Gold Price for new feature inputs

Help analyze market correlations

Support research and investment decisions

**Conclusion**

This Gold Price Prediction Model provides a high-accuracy financial forecasting tool using machine learning.
It demonstrates how market indicators like Silver, Oil, and Currency price impact Gold trends.
