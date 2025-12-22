**🪙 Gold Price Prediction Model using Machine Learning**

This project is a Machine Learning-based Gold Price Prediction System developed using Python and Random Forest Regression.
The model predicts the future price of Gold (GLD index value) based on financial indicators.

**📌 Project Overview**

Gold is one of the most important investment assets, and its price depends on multiple market factors.
This project analyzes a historical Gold dataset and builds a predictive model using regression techniques.

**🔄 Workflow Includes**

📂 Data loading

📊 Exploratory analysis

📈 Correlation study

✂️ Train-test split

🤖 Model training

🧪 Evaluation and prediction

**🤖 Machine Learning Algorithm Used – Random Forest Regressor**

🌳 Ensemble-based algorithm

🌲 Creates multiple decision trees

🛡️ Reduces overfitting & improves stability

🧮 Ideal for numerical prediction tasks

**📂 Dataset Details**

🏛️ Source: Gold Price Historical Dataset

🎯 Target Variable: GLD (Gold Price Index)

**📉 Other Market Features Used**

📌 SPX (S&P 500 Index)

🛢️ USO (Oil Price)

🥈 SLV (Silver Price)

💱 EUR/USD (Currency Exchange Rate)

🗑️ Date column was removed from features

**🛠️ Technologies & Libraries**

🐍 Python

🔢 NumPy

📊 Pandas

📉 Matplotlib

🌈 Seaborn

🧠 Scikit-learn

📓 Jupyter Notebook / Google Colab

**🏗️ Project Workflow**
📥 Data Collection

Loaded the CSV dataset into a pandas DataFrame.

**📊 Data Analysis**

Checked dataset shape

Verified datatypes

Confirmed no missing values

**📈 Exploratory Data Visualization**

Generated correlation heatmap

Found strong positive correlation between GLD & SLV

**🧹 Feature Engineering**

Removed Date column

Split data into:

🧾 Features: SPX, USO, SLV, EUR/USD

🎯 Target: GLD

**✂️ Train–Test Split**

80% training

20% testing

Random state for reproducibility

🏋️ Model Training

Random Forest Regressor trained on training data

🧪 Model Evaluation

Evaluated using R² Score

📈 Model Performance

🥇 R² Score: ~0.98 – 0.99

🚀 Excellent predictive accuracy

🟰 Predicted values closely match actual values

🔮 Prediction System

The trained model can:

📊 Predict Gold Price for new inputs

🔍 Analyze market correlations

📈 Support research & investment decisions

🏁 Conclusion

This Gold Price Prediction Model provides a high-accuracy financial forecasting tool using Machine Learning.
It showcases how indicators like Silver, Oil, and Currency rates impact Gold price behavior.
