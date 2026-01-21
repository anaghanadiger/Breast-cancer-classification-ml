# Breast Cancer Classification (Machine Learning Project)

This project uses the Breast Cancer Wisconsin Dataset to classify tumors as **malignant or benign** using machine learning. The goal is to build a reliable model that supports early diagnosis while prioritizing **recall**, since missing malignant cases is risky in medical settings.

---

## Project Overview

1. Data understanding and preprocessing  
2. Train–test split and scaling  
3. Baseline model: Logistic Regression  
4. Final model: Random Forest  
5. Model evaluation and comparison  
6. Confusion matrices  
7. Feature importance analysis  
8. Key insights and conclusions  

---

## Model Results

### Logistic Regression
- Accuracy: ~96%
- Precision: ~97%
- Recall: ~93%
- F1-Score: ~95%

### Random Forest
- Accuracy: ~97%
- Precision: 100%
- Recall: ~96%
- F1-Score: ~98%
- ROC-AUC: ~0.99

---

## Insights

- Random Forest performs better, especially in recall, which is crucial in medical diagnosis.
- Confusion matrices show fewer false negatives for Random Forest compared to Logistic Regression.
- Feature importance reveals that tumor size and shape irregularity are key predictors of malignancy.
- The model's behavior matches medical understanding, increasing trust in its predictions.

---

## Screenshots

Screenshots included:
- Correlation Heat Map
- Logistic Regression confusion matrix  
- Random Forest confusion matrix  
- Random Forest feature importance  

Stored in the `screenshots/` folder.

## Correlation Heat Map
<img width="1072" height="992" alt="Correlation" src="https://github.com/user-attachments/assets/81759325-c389-4f34-b2c5-0095c9c51b72" />

## Confusion Matrix – Logistic Regression
<img width="498" height="455" alt="Log_CM" src="https://github.com/user-attachments/assets/f7cf1e55-6f84-4852-bc35-a134c775f7a5" />

## Confusion Matrix – Random Forest
<img width="498" height="455" alt="RF_CM" src="https://github.com/user-attachments/assets/81017461-f406-4a0a-b00b-3d846c9eec14" />

## Feature Importance – Random Forest
<img width="989" height="590" alt="RF_FI" src="https://github.com/user-attachments/assets/e5187463-6f3f-46f1-9648-ccc9263380ad" />



---

## Technologies Used
- Python  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
