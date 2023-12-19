# Diabetes-Prediction-System
This project aims to develop a diabetes prediction system using machine learning techniques.
# Introduction
* This project aims to develop a diabetes prediction system using machine learning techniques.
* The dataset used for this project is sourced from the National Institute of Diabetes and Digestive and Kidney Diseases, containing diagnostic measurements to predict whether a patient has diabetes.
* The dataset consists of female patients, at least 21 years old, of Pima Indian heritage.
# Dataset Overview
* Pregnancies: Number of pregnancies
* Glucose: Glucose level in blood
* BloodPressure: Blood pressure measurement
* SkinThickness: Thickness of the skin
* Insulin: Insulin level in blood
* BMI: Body mass index
* DiabetesPedigreeFunction: Diabetes percentage
* Age: Age of the patient
* Outcome: Binary result (1 for Yes, 0 for No) indicating diabetes presence or absence
# Project Steps
# Step 1: Loading and Analyzing the Dataset
* Load the dataset, analyze its shape, and check the number of columns.
* Examine data types, display the top and bottom 5 rows.
* Rename columns if necessary and perform data cleaning.
# Step 2: Dealing with Outliers
* Identify outliers in the dataset.
* Utilize the winsorization technique to handle outliers effectively.
# Step 3: Data Visualization
* Employ pair plots to visualize relationships between different columns.
* Use countplot to show the distribution of diabetic and non-diabetic individuals.
# Step 4: Modelling
* Implement various machine learning models for diabetes prediction.
  * Decision Tree Classifier
  * Random Forest Classifier
  * KNeighbor Classifier
  * XGBoost Classifier
  * AdaBoost Classifier
* Evaluate the models and report accuracy.
* Highlight the best-performing model (e.g., Decision Tree with 75.32% accuracy).
# Conclusion
This project demonstrates the process of developing a diabetes prediction system using machine learning. The selected model, the Decision Tree Classifier, provides a notable accuracy of 75.32% in predicting diabetes based on the given diagnostic measurements. Feel free to explore and enhance the project for further improvements.
