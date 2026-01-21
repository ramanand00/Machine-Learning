# UNIT 10: Model Evaluation and Performance Metrics

## 10.1 Introduction

Model evaluation is the process of **measuring how well a machine learning model performs**.

**It ensures:**

- The model makes accurate predictions  
- The model generalizes well to new data  
- Avoids overfitting or underfitting  

---

## 10.2 Types of Evaluation Metrics

Metrics depend on the type of ML task:

- **Regression Metrics** → For predicting continuous values  
- **Classification Metrics** → For predicting categories  

---

## 10.3 Regression Evaluation Metrics

### 10.3.1 Mean Absolute Error (MAE)

Average of absolute differences between predicted and actual values  

MAE = (1/n) * Σ |yi - ŷi|

perl
Copy code

- ✔ Easy to interpret  

### 10.3.2 Mean Squared Error (MSE)

Average of squared differences between predicted and actual values  

MSE = (1/n) * Σ (yi - ŷi)^2

mathematica
Copy code

- ✔ Penalizes large errors  

### 10.3.3 Root Mean Squared Error (RMSE)

Square root of MSE  

RMSE = √MSE

csharp
Copy code

- ✔ Same units as target variable  

### 10.3.4 R-Squared (R²)

Measures how well predictions fit the data  

R² = 1 - (SS_res / SS_tot)

yaml
Copy code

- Value between 0 and 1  
- Higher → Better fit  

---

## 10.4 Classification Evaluation Metrics

### 10.4.1 Accuracy

Accuracy = Correct Predictions / Total Predictions

markdown
Copy code

- ✔ Simple, widely used  
- ❌ Not good for imbalanced datasets  

### 10.4.2 Precision

Percentage of predicted positives that are actually positive  

Precision = TP / (TP + FP)

csharp
Copy code

- ✔ Important when false positives are costly  

### 10.4.3 Recall (Sensitivity)

Percentage of actual positives correctly predicted  

Recall = TP / (TP + FN)

sql
Copy code

- ✔ Important when false negatives are costly  

### 10.4.4 F1-Score

Harmonic mean of precision and recall  

F1 = 2 * (Precision * Recall) / (Precision + Recall)

yaml
Copy code

- ✔ Balances precision and recall  

### 10.4.5 Confusion Matrix

A table that shows model predictions vs actual values:

| Actual \ Predicted | Positive | Negative |
|------------------|---------|---------|
| Positive          | TP      | FN      |
| Negative          | FP      | TN      |

- **TP** → True Positive  
- **TN** → True Negative  
- **FP** → False Positive  
- **FN** → False Negative  

> Helps calculate **precision, recall, and F1-score**.  

---

## 10.5 ROC Curve and AUC

- **ROC (Receiver Operating Characteristic) curve** plots:  
  True Positive Rate (Recall) vs False Positive Rate  
- **AUC (Area Under Curve)** measures model’s ability to distinguish classes  
- Value between 0 and 1 → Higher is better  

---

## 10.6 Cross-Validation (Revisited)

**K-Fold Cross-Validation** evaluates model reliably and reduces bias from single train-test split.

**Steps:**

1. Split dataset into K parts  
2. Train K times on K-1 parts  
3. Test on remaining part  
4. Average results  

---

## 10.7 Bias-Variance Tradeoff (Revisited)

- **High bias → Underfitting**  
- **High variance → Overfitting**  
- **Goal → Balance bias and variance for best generalization**  

---

## 🎯 Exam-Oriented Questions

1. What is model evaluation?  
2. Explain MAE, MSE, and RMSE.  
3. Define accuracy, precision, and recall.  
4. What is F1-score?  
5. Explain confusion matrix.  
6. What is ROC and AUC?  
7. Why is cross-validation important?
