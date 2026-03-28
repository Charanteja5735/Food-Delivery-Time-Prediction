# Food-Delivery-Time-Prediction
This repository contains a machine learning project designed to accurately predict food delivery times using regression algorithms like Random Forest and XGBoost
This project is a web-based application that predicts food delivery time 
using: 
●  Web Development (Frontend + Backend) 
●  Google Maps API (for distance & route) 
●  Machine Learning (for prediction) 
�
�
Goal: 
To give accurate delivery time based on real conditions instead of rough 
estimates. 
How the System Works (Simple Flow) 
1. User enters: 
○ Restaurant location 
○ Delivery location 
○ Preparation time 
○ Traffic level 
2. Backend calls Google Maps API 
○ Gets distance between locations 
3. Data is sent to ML Model 
4. Model predicts: 
○ ⏱ Delivery Time (in minutes) 
5. Result is displayed on website 
=> Working Architecture 
User (Browser) 
↓ 
Frontend (HTML Form) 
↓ 
Flask Backend (Python) 
↓ 
Google Maps API → Distance 
↓ 
ML Model (Regression) 
↓ 
Prediction Result 
↓ 
Displayed on Website 
=>  Technologies Used 
�
�
Web Development 
● HTML, CSS → User Interface 
● Flask → Backend server 
�
�
Machine Learning 
● Scikit-learn 
● Linear Regression 
�
�
API 
● Google Maps Distance Matrix API 
=> Machine Learning Explanation 
�
�
Problem Type: 
�
�
Regression Problem 
(Because output is a number → time in minutes) 
�
�
Input Features: 
● Distance (from Maps) 
● Preparation time 
● Traffic level 
�
�
Output: 
● Delivery Time 
�
�
Model Logic (Simple Understanding) 
● Distance is more → time increases 
● Traffic is high → time increases 
● Prep time is high → delay increases 
The model learns this relationship from data.
