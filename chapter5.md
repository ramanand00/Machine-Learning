# UNIT 5: Supervised Learning

## 5.1 Introduction to Supervised Learning

**Supervised Learning** is a type of Machine Learning where the model is trained using **labeled data**.

**Labeled Data means:**  
- Input data with correct output  

**Basic Idea:**  
> Input (X) → Model → Output (Y)  

**Example:**

| Study Hours | Marks |
|------------|-------|
| 5          | 60    |
| 8          | 85    |

Here:  
- Input → Study Hours  
- Output → Marks  

---

## 5.2 Types of Supervised Learning

Two main categories:

1. **Regression**  
2. **Classification**  

---

## 5.3 Regression

### 5.3.1 What is Regression?

- Used when output is **continuous (numerical)**  

**Examples:** House price prediction, Temperature prediction, Salary prediction  

### 5.3.2 Simple Linear Regression

- Relationship between **one input** and **one output**  

**Equation:**  
> y = mx + c  

Where:  
- y = dependent variable  
- x = independent variable  
- m = slope  
- c = intercept  

**Example:** Predicting marks based on study hours  

### 5.3.3 Multiple Linear Regression

- Uses **more than one input feature**  

**Example:** Predicting house price using: Area, Number of rooms, Location  

**Equation:**  
> y = m1x1 + m2x2 + ... + c  

### 5.3.4 Polynomial Regression

- Used when data is **not linear**  
- Fits a **curve** instead of a straight line  

**Example:** Growth rate prediction  

### 5.3.5 Regression Evaluation Metrics

**Mean Absolute Error (MAE):**  
> MAE = Average of |Actual − Predicted|  
✔ Easy to understand  

**Mean Squared Error (MSE):**  
> MSE = Average of (Actual − Predicted)²  
✔ Penalizes large errors  

**R-Squared (R²):**  
- Measures how well the model fits data  
- Value between 0 and 1  
✔ Higher value → Better model  

---

## 5.4 Classification

### 5.4.1 What is Classification?

- Used when output is **categorical**  

**Examples:** Spam or Not Spam, Pass or Fail, Disease Yes or No  

### 5.4.2 Logistic Regression

- Despite its name, used for **classification**  
- Output: Probability between 0 and 1  
- Used for **binary classification**  

### 5.4.3 K-Nearest Neighbors (KNN)

- Classifies data based on **nearest neighbors**  
- Uses distance (usually Euclidean)  

**Example:** Classifying students based on similarity  

✔ Simple  
❌ Slow for large datasets  

### 5.4.4 Naive Bayes Algorithm

- Based on **Bayes Theorem**  
- Assumes features are **independent**  

**Used in:** Spam detection, Text classification  

✔ Fast  
✔ Works well with text data  

### 5.4.5 Decision Tree

- Uses a **tree-like structure**  
- Decisions based on conditions  

**Example:**  

Is age > 18?
├─ Yes → Allow
└─ No → Deny

yaml
Copy code

✔ Easy to understand  
❌ Can overfit  

### 5.4.6 Support Vector Machine (SVM)

- Finds the best **boundary (hyperplane)**  
- Separates different classes  

✔ Works well for high-dimensional data  
❌ Computationally expensive  

---

## 5.5 Classification Evaluation Metrics

**Accuracy:**  
> Accuracy = Correct Predictions / Total Predictions  
✔ Simple  
❌ Not good for imbalanced data  

**Precision:** How many predicted positives are actually positive  

**Recall:** How many actual positives are correctly predicted  

**F1-Score:** Balance between precision and recall  

**Confusion Matrix:**

| Actual \ Predicted | Yes | No |
|------------------|-----|----|
| Yes               | TP  | FN |
| No                | FP  | TN |

> Helps analyze model errors  

---

## 5.6 Comparison: Regression vs Classification

| Feature     | Regression          | Classification       |
|------------|-------------------|--------------------|
| Output     | Continuous         | Categorical        |
| Example    | House price        | Spam detection     |
| Algorithms | Linear Regression  | KNN, SVM           |
| Metrics    | MAE, MSE           | Accuracy, F1        |

---

## 5.7 Advantages of Supervised Learning

- ✔ High accuracy  
- ✔ Clear performance evaluation  
- ✔ Well-understood algorithms  

---

## 5.8 Limitations of Supervised Learning

- ❌ Requires labeled data  
- ❌ Labeling is costly  
- ❌ Overfitting risk  

---

## 🎯 Exam-Oriented Questions

1. Define supervised learning.  
2. Differentiate between regression and classification.  
3. Explain linear regression.  
4. Write short notes on:  
   - KNN  
   - Decision Tree  
   - SVM  
5. What is a confusion matrix?  
6. Explain precision and recall.  