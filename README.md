# 📊 Student Math Score Prediction Model

## Overview  
This project builds a **Regression Model** to predict a **student's Math score** using Kaggle’s **StudentPerformance** dataset. The model analyzes various student attributes, such as **gender, parental education, and test preparation status**, to provide predictions.

## Dataset: Kaggle's StudentPerformance  
- The dataset includes students' demographic details and scores in **Math, Reading, and Writing**.  
- Key features:  
  - **Gender**  
  - **Race/Ethnicity**  
  - **Parental Level of Education**  
  - **Lunch Type** (Standard/Reduced)  
  - **Test Preparation Course Completion**  
  - **Reading and Writing Scores**  

🔗 **Dataset Source**: [Kaggle - Student Performance](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)  

## Project Workflow  

### 1️⃣ Data Preprocessing  
✔ Handle **missing values** (if any).  
✔ Convert **categorical variables** using **OneHotEncoding**.  
✔ Standardize **numerical features** using **StandardScaler**.  

### 2️⃣ Model Selection  
The following regression models were tested:  
✔ **Linear Regression**  
✔ **Ridge Regression**  
✔ **Lasso Regression**  
✔ **K-Nearest Neighbors (KNN) Regressor**  
✔ **Decision Tree Regressor**  
✔ **Random Forest Regressor**  

### 3️⃣ Model Training & Evaluation  
✔ **Train-Test Split** (80%-20%)  
✔ **Model Fitting** on training data  
✔ **Evaluation Metrics**:  
   - **R² Score** (Coefficient of Determination)  
   - **Mean Squared Error (MSE)**  
   - **Mean Absolute Error (MAE)**  

