# Agricultural-Crop-Model

This project explores how basic soil metrics—Nitrogen (N), Phosphorous (P), Potassium (K), and pH—can be used to predict the most suitable crop for a given field by building a multi-class logistic regression model. Since testing all soil components can be expensive and time-consuming, this project also aims to identify the single most important feature for crop prediction.

---

# Dataset Overview

The dataset used is "soil_measures.csv" and contains the following columns:

- N – Nitrogen content ratio in the soil  
- P – Phosphorous content ratio in the soil  
- K – Potassium content ratio in the soil  
- pH – Soil pH value  
- crop – The crop most suited to the soil conditions (Target Variable)

Each row represents soil measurements from a particular field. The goal is to recommend the optimal crop for that soil profile.


# Project Objectives

1. Build a **multi-class classification model** to predict the appropriate crop based on soil characteristics.
2. Evaluate the **individual predictive power** of each soil metric (N, P, K, pH).
3. Identify the **single most influential feature** for accurate crop prediction.

---

# Tools & Libraries Used

1. Python
2. Pandas for data manipulation
3. Scikit-learn for modeling and evaluation
4. Logistic Regression for classification
5. F1 Score for performance evaluation  

---

# Workflow Summary

1. Import Necessary Libraries 
2. Load Dataset 
3. Explore & Clean Data  
4. Split Data into Features (`X`) and Target (`y`) 
5. Train Logistic Regression Models using each feature independently  
6. Evaluate Model Performance using F1 Score  
7. Identify Best Predictive Feature

---

# RESULTS

Each soil metric was used individually to train a logistic regression model. F1 scores were computed to evaluate performance. The metric that produced the "highest F1 score" was determined to be the most predictive for recommending crops.


SOURCE: Datacamp

