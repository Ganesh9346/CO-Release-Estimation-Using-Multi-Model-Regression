📌 Project Title

Carbon Emission Prediction Using Machine Learning

📄 Project Description

A machine learning system that predicts vehicle CO₂ emissions based on engine size, cylinders, fuel consumption, and other features. The project includes data cleaning, preprocessing, EDA, feature engineering, model training, and performance comparison.

📂 Dataset

Source: CO₂ Emissions Dataset (Canada)

Rows: 7385

Columns: 12

Target Variable: CO2 Emissions (g/km)

🔧 Tech Stack / Libraries

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

🧹 Data Processing

Handled outliers using IQR

Encoded categorical variables (One-Hot & Frequency Encoding)

Performed scaling for ML models

Selected top correlated features

📊 EDA

Distribution plots

Scatter plots

Correlation heatmap

Categorical analysis

🤖 Models Used

Linear Regression

Polynomial Regression

KNN Regression

Support Vector Regression

Decision Tree Regressor

Random Forest Regressor

🏆 Best Model

Random Forest Regression

R² Score: ~0.97

RMSE: ~9.1

🧪 How to Run
pip install -r requirements.txt
python main.py

🎯 Features

Predicts CO₂ emissions from user input

Clean, interactive prediction function

Complete ML pipeline from raw data to model deployment

📌 Future Improvements

Deploy model using Flask/Streamlit

Add more environmental features

Convert notebook to web app
