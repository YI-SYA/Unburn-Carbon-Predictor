Project Overview

The Unburn Carbon Predictor is a machine learning-based project designed to predict unburned carbon levels in coal combustion processes. This project aims to optimize combustion efficiency by analyzing key factors influencing unburned carbon levels using various regression models, including LightGBM, Random Forest, and Multiple Linear Regression.

Problem Statement

Unburned carbon is a critical parameter in coal-fired power plants as it directly affects combustion efficiency and emissions. High levels of unburned carbon indicate incomplete combustion, leading to increased fuel consumption and environmental impact. This project focuses on predicting unburned carbon levels using machine learning techniques to assist in optimizing boiler operations.

Dataset

The dataset consists of 89 samples with 21 features, including fuel properties, combustion parameters, and emissions data. Key features include:

Carbon content

Heating value (Nilai Kalor)

CO and CO2 emissions

Airflow parameters (PA Flow, SA Flow, O2 levels)

Fuel moisture content (Total Moisture, Surface Moisture, Inherent Moisture)

Methodology

Data Preprocessing: Handling missing values, scaling numerical features, and encoding categorical variables.

Exploratory Data Analysis (EDA): Visualizing correlations between variables, especially the relationship between carbon content and heating value.

Feature Selection: Identifying the most influential parameters affecting unburned carbon.

Model Training: Comparing multiple machine learning models:

LightGBM Regression (Gradient boosting-based approach)

Random Forest Regression

Multiple Linear Regression

Model Evaluation: Using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² score to assess model performance.

Results

The LightGBM model achieved the best performance, demonstrating high accuracy in predicting unburned carbon levels, with a significant reduction in prediction errors compared to traditional regression methods. The confusion matrix and evaluation metrics further validate the model's effectiveness.

Key Insights

Carbon content and heating value exhibit a strong correlation, impacting combustion efficiency.

Optimizing air-to-fuel ratio can significantly reduce unburned carbon.

LightGBM outperforms traditional models in predicting unburned carbon with high accuracy.

Future Work

Integration with real-time boiler monitoring systems to provide predictive maintenance insights.

Deployment as a web-based application using Streamlit for easy user interaction.

Expanding the dataset for improved generalization across different power plant conditions.

Technologies Used

Python (Pandas, NumPy, Scikit-learn, LightGBM, Matplotlib, Seaborn)

Machine Learning (Supervised Regression Models)

Data Visualization (Seaborn, Matplotlib)

Deployment Tools (Streamlit, Flask - Future Work)

Conclusion

This project demonstrates the effectiveness of machine learning in predicting unburned carbon levels, contributing to improved combustion efficiency in coal power plants. By leveraging advanced regression models, this solution aids in reducing fuel wastage, lowering emissions, and enhancing overall boiler performance.
