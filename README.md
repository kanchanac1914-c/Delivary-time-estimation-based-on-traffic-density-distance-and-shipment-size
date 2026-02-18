# 🚚 Delivery Time Estimation Based on Traffic Density, Distance, and Shipment Size

📌 Project Overview
This project focuses on predicting delivery time using Machine Learning techniques based on three major factors:
📍 Distance (in kilometers)
🚦 Traffic Density
📦 Shipment Size

The objective is to build a predictive model that can accurately estimate delivery time and help logistics companies optimize routes, reduce delays, and improve customer satisfaction.



🎯 Aim

To develop a machine learning model that estimates delivery time using distance, traffic density, and shipment size as input features.



🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Gradio (for UI deployment)

📂 Dataset Description

The dataset contains the following features:

| Feature Name        | Description                               |
| ------------------- | ----------------------------------------- |
| distance_km         | Distance between source and destination   |
| traffic_density     | Traffic condition (Low / Medium / High)   |
| shipment_size       | Size of shipment (Small / Medium / Large) |
| delivery_time_hours | Actual delivery time (Target Variable)    |


🔍 Project Workflow
1️⃣ Data Preprocessing
Handling missing values using mean/mode imputation
Encoding categorical variables
Feature scaling

2️⃣ Exploratory Data Analysis (EDA)
Scatter plots (Distance vs Delivery Time)
Traffic density impact analysis
Distribution plots of delivery time
Correlation heatmap

3️⃣ Model Building
Different regression algorithms were tested:
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Random Forest gave the best performance.

4️⃣ Model Evaluation
Model performance was evaluated using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score

types

📊 Results

The model successfully predicts delivery time with good accuracy.
Key Observations:
Delivery time increases with distance
High traffic significantly increases delivery delay
Large shipment size slightly increases delivery time

🖥️ Deployment

The model is deployed using Gradio, allowing users to input:
Distance
Traffic Density
Shipment Size
And receive predicted delivery time instantly.

🚀 Future Improvements

Add weather conditions as a feature
Use real-time traffic API integration
Implement Deep Learning models
Deploy on cloud (AWS / Azure)
