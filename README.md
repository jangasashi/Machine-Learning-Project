Heart Disease Prediction Report
Problem Statement:
The goal of this project is to build a system that predicts if a patient has heart disease based on their health data. Early detection can help prevent serious complications. We aim to use patient information to predict whether they have heart disease or not.

Dataset Overview
The dataset contains various health features for each patient, such as:

age: Age of the patient
sex: Gender (0 = female, 1 = male)
chest pain type: Type of chest pain (1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic)
resting blood pressure: Blood pressure when at rest
serum cholesterol: Cholesterol level
fasting blood sugar: Blood sugar level (1 = sugar > 120mg/dL, 0 = sugar < 120mg/dL)
resting electrocardiogram: ECG result (0 = normal, 1 = abnormal, 2 = left ventricular hypertrophy)
maximum heart rate: Highest heart rate during exercise
exercise-induced angina: Whether the patient experiences chest pain during exercise (0 = no, 1 = yes)
oldpeak: Depression caused by exercise
ST slope: Slope of the peak exercise ST segment (1 = upward, 2 = flat, 3 = downward)
target: Whether the patient has heart disease (0 = no, 1 = yes)
Data Cleaning and Preprocessing
We cleaned the dataset by:

Handling missing values
Converting categorical data into a format that machine learning models can understand (encoding categorical features)
Scaling numerical features
Splitting the data into training and testing sets to evaluate the models
Model Building and Performance
We used two machine learning models:

Logistic Regression: A basic model for predicting binary outcomes.
Random Forest Classifier: A more advanced model that uses multiple decision trees to make predictions.
We evaluated both models using accuracy, confusion matrix, and classification report.

Key Insights
Important Features: The most important factors for predicting heart disease were:

ST slope
sex
exercise-induced angina
chest pain type
fasting blood sugar
Model Comparison: The Random Forest model performed the best, with an accuracy of 95%, compared to 86% for Logistic Regression.

Conclusion
This project successfully built a heart disease prediction system. The Random Forest model performed well with an accuracy of 95%. Key features such as chest pain type, exercise-induced angina, and ST slope were found to be important indicators of heart disease. The model can be used to assist in early heart disease detection.

Future improvements could include using additional data or exploring different machine learning models.
