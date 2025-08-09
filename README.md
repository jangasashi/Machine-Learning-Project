❤️ Heart Disease Prediction Report


📌 Problem Statement
The goal of this project is to predict if a patient has heart disease based on their health data.
Early detection can help prevent serious complications.
We aim to use patient information to predict the presence or absence of heart disease.

📊 Dataset Overview
The dataset contains various health features for each patient:

Feature	Description
age	Age of the patient
sex	Gender (0 = female, 1 = male)
chest pain type	(1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic)
resting blood pressure	Blood pressure when at rest
serum cholesterol	Cholesterol level
fasting blood sugar	(1 = sugar > 120mg/dL, 0 = sugar < 120mg/dL)
resting electrocardiogram	(0 = normal, 1 = abnormal, 2 = left ventricular hypertrophy)
maximum heart rate	Highest heart rate during exercise
exercise-induced angina	(0 = no, 1 = yes)
oldpeak	Depression caused by exercise
ST slope	(1 = upward, 2 = flat, 3 = downward)
target	(0 = no heart disease, 1 = has heart disease)

🛠 Data Cleaning & Preprocessing
✅ Handled missing values

🔄 Encoded categorical features into numerical format

📏 Scaled numerical features for consistency

✂️ Split data into training and testing sets for evaluation

🤖 Model Building & Performance
We trained two machine learning models:

Logistic Regression – A basic binary classification model

Random Forest Classifier – An advanced ensemble model using multiple decision trees

Evaluation Metrics Used:

Accuracy

Confusion Matrix

Classification Report

🔍 Key Insights
Important Features for prediction:

ST slope

sex

exercise-induced angina

chest pain type

fasting blood sugar

Model Comparison:

Random Forest – 🏆 95% accuracy

Logistic Regression – 86% accuracy

✅ Conclusion
This project successfully built a Heart Disease Prediction System.
The Random Forest model achieved the best results with 95% accuracy.
Key features such as chest pain type, exercise-induced angina, and ST slope were found to be strong indicators of heart disease.

🚀 Future Improvements
Adding more patient data for better generalization

Trying advanced deep learning models

Feature engineering for improved accuracy


