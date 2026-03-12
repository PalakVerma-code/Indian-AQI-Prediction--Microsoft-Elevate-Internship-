# Indian-AQI-Prediction--Microsoft-Elevate-Internship-
This repository contains a Machine Learning solution for predicting the Air Quality Index (AQI) in Indian urban areas. By analyzing pollutants like PM2.5 and $NO_2$, the model provides early warnings for public health safety

Indian Air Quality Index (AQI) Prediction
Microsoft Elevate AICTE Internship - Capstone Project
📌 Project Overview
Air pollution is a critical challenge in Indian urban areas, affecting public health and environmental stability. This project implements a Machine Learning solution to predict the Air Quality Index (AQI) based on the concentration of various pollutants. The system aims to provide accurate forecasts that can assist municipal corporations in issuing health advisories and implementing pollution control measures like the "Odd-Even" scheme.

🛠️ Technology Stack
Language: Python 3.x

Libraries: * Pandas: For data manipulation and cleaning

NumPy: For numerical computations

Scikit-Learn: For implementing the Random Forest algorithm

Seaborn & Matplotlib: For generating performance visualizations

Environment: Google Colab

📊 Dataset Information
Source: Central Pollution Control Board (CPCB), India.

Features Used: * PM2.5 & PM10: Particulate Matter (crucial for Indian air quality)

NO2: Nitrogen Dioxide

CO: Carbon Monoxide

Target Variable: AQI (Air Quality Index)

🤖 Algorithm & Methodology
The project utilizes the Random Forest Regressor.


Why Random Forest? It is an ensemble learning method that handles non-linear relationships and outliers in seasonal Indian pollution data more effectively than simple regression models.

Training: The data is split into an 80% training set and a 20% testing set to ensure the model generalizes well to new data.

📈 Results
The model achieved a significant R-squared (R2) Score, indicating high accuracy in predicting AQI levels.

The visualization (Actual vs. Predicted) shows that the model successfully identifies trends in pollution spikes.

🚀 How to Run
Download the .ipynb file from this repository.

Open it in Google Colab.

Run the cells sequentially to see the data cleaning, model training, and output graphs.

🔮 Future Scope
Integration of real-time data from IoT-based sensors across Indian cities.

Deployment as a mobile application for real-time citizen alerts.

Using advanced techniques like Long Short-Term Memory (LSTM) for better time-series forecasting.

Presented By: [Palak Verma]
College: [CSJMU ,kanpur]


Internship: Microsoft Elevate AICTE Internship (Feb 2026)
