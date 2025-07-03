# HEART-DIEASE-PRIDECTION-MODEL
HEART DIEASE PREDCITION MODEL USING LOGISTIC REGRESSION 


Project Overview
This is a minor machine learning project designed to:

Analyze patient clinical data

Train a binary classification model

Predict the likelihood of heart disease in new cases

📂 Dataset Details
Source: UCI Heart Disease Dataset

Features:
Includes attributes such as:

Age

Sex

Chest Pain Type

Resting Blood Pressure

Cholesterol

Fasting Blood Sugar

Resting ECG

Max Heart Rate

Exercise Induced Angina

ST Depression

Slope of Peak Exercise ST Segment

Number of Major Vessels

Thalassemia

Target Variable:

1 = presence of heart disease

0 = no heart disease

🧠 ML Pipeline
1. 📊 Data Preprocessing
Data loading with pandas

Exploratory data analysis: .info(), .describe(), .value_counts()

Checking and handling missing values

Feature-target split: X and y

2. 🔁 Train-Test Split
Using train_test_split with stratification to preserve class distribution (80% train / 20% test)

3. 🤖 Model Building
Algorithm: Logistic Regression (sklearn.linear_model.LogisticRegression)

Model training on training data

4. ✅ Evaluation
Evaluated on both training and test data using:

accuracy_score

Print statements display the training and test accuracy

📈 Sample Output
python
Copy
Edit
Accuracy on training data : 0.85
Accuracy on testing data  : 0.81
📡 Prediction System
A simple prediction system is built to test the model with a new patient's data using:

python
Copy
Edit
given_data = (65,1,0,135,254,0,0,127,0,2.8,1,1,3)
Prediction:

1: Person likely has heart disease

0: Person is not likely to have heart disease

