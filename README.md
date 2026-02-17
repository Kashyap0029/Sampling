# Sampling
### Credit Card Classification Assignment

---

## Assignment Objective

The main objective of this assignment is to analyze the effect of different sampling techniques on machine learning models using an imbalanced dataset.

The tasks performed are:

1. Convert the dataset into a balanced class dataset  
2. Apply five different sampling techniques (Sampling1–Sampling5)  
3. Train five different machine learning models (M1–M5)  
4. Evaluate performance using accuracy  
5. Determine which sampling technique gives the highest accuracy for each model  

---

## Dataset Information

- **Dataset Name:** Creditcard_data.csv  
- **Type:** Binary Classification  
- **Target Column:** `Class`  

Class Labels:
- `0` → Normal Transaction  
- `1` → Fraudulent Transaction  

The dataset is imbalanced, therefore sampling methods are applied before model training.

---

## Sampling Techniques Used

| Sampling Code | Technique |
|---------------|------------|
| Sampling1 | Random Over Sampling |
| Sampling2 | Random Under Sampling |
| Sampling3 | SMOTE |
| Sampling4 | SMOTE + ENN |
| Sampling5 | Balanced Random Forest |

---

## Machine Learning Models Used

| Model Code | Algorithm |
|------------|------------|
| M1 | Logistic Regression |
| M2 | Decision Tree |
| M3 | Random Forest |
| M4 | Support Vector Machine |
| M5 | Gaussian Naive Bayes |

---

## Methodology

1. Load dataset  
2. Separate features and target variable  
3. Apply selected sampling technique  
4. Split dataset into training and testing sets  
5. Train the model  
6. Predict on test data  
7. Calculate accuracy  
8. Store results in a performance matrix  
9. Identify the best model–sampling combination  

---

## 📈 Performance Matrix (Accuracy %)

<img width="928" height="466" alt="image" src="https://github.com/user-attachments/assets/45d54513-db71-4c70-8864-4c834b3f9098" />

