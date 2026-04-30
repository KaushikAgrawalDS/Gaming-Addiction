# Gaming-Addiction

Overview
Gaming addiction is becoming a serious issue among students due to easy access to smartphones and the internet. This project aims to analyze student behavior and predict whether a student is addicted to gaming using machine learning techniques.

We used a real-world dataset and applied multiple classification models to identify key factors contributing to gaming addiction.

Objective

Analyze gaming behavior among students
Identify factors influencing gaming addiction
Build machine learning models to predict addiction
Compare model performance and select the best one

Dataset Information

Source: Nature.com dataset
Total Records: 1061 students
Features: 21 input features + 1 target variable
Target: Addicted (Yes/No)
Distribution:
Not Addicted: ~695
Addicted: ~326

Data Preprocessing

We performed several preprocessing steps:

Removed irrelevant columns (age, education, etc.)
Handled inconsistent categorical values
Converted time format (HH:MM → numeric hours)
Removed outliers using IQR method
Applied:
Label Encoding
One-Hot Encoding
Exploratory Data Analysis (EDA)

Key insights:

Gaming Time → Strongest factor affecting addiction
Late-night sleep (2 AM+) → Higher addiction
Battle Royale games → Highest addiction rate
Addicted students → Slightly lower CGPA
Less social interaction → Higher addiction

Models Used

We implemented and compared 4 models:

Logistic Regression
Decision Tree
K-Nearest Neighbors (KNN)
Naive Bayes
