# Gaming Addiction Prediction using Machine Learning

## Overview
Gaming addiction is becoming a serious issue among students due to the easy availability of smartphones and the internet.  
This project analyzes student behavior and predicts whether a student is addicted to gaming using machine learning models.

---

## Objective
- Analyze gaming behavior of students  
- Identify key factors contributing to addiction  
- Build classification models  
- Compare model performance  

---

##  Dataset
- Source: Nature.com  
- Records: 1061 students  
- Features: 21 + 1 target variable  
- Target: `Addicted (Yes/No)`

---

## Data Preprocessing
- Removed irrelevant columns  
- Handled inconsistent categorical values  
- Converted time format (HH:MM → numeric)  
- Removed outliers using IQR  
- Applied encoding:
  - Label Encoding  
  - One-Hot Encoding  

---

## Exploratory Data Analysis
Key findings:
- Gaming time is the strongest factor  
- Late-night sleep increases addiction  
- Battle Royale games are most addictive  
- Addicted students have slightly lower CGPA  

---

## Models Used
- Logistic Regression  
- Decision Tree  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  

---

## Model Performance

| Model                | Accuracy |
|---------------------|---------|
| Logistic Regression | 94.3%   |
| KNN                 | 94.3%   |
| Naive Bayes         | 93.8%   |
| Decision Tree       | 93.1%   |

 **Final Model:** Logistic Regression

---

##  Results
- High accuracy with good generalization  
- Minimal overfitting  
- Reliable classification of addicted vs non-addicted students  

---

## Future Scope
- Add mental health data  
- Include social media usage  
- Apply advanced models (XGBoost, Random Forest)  
- Build real-time prediction system  

--
## Project structure
## 📂 Project Structure

```text
Gaming-addiction/
├── data/
│   ├── raw/
│   │   └── raw.csv
│   ├── processed/
│   │   └── processed
│   └── encoded/
│       └── encoded
│
├── notebooks/
│   ├── Data_Pre_Processing.ipynb
│   ├──EDA & Visualization.ipynb
│   └── Model Training and Evaluation.ipynb
│
│
├── README.md
```
