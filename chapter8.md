# UNIT 8: Ensemble Learning

## 8.1 Introduction to Ensemble Learning

**Ensemble Learning** is a technique where multiple machine learning models are combined to produce a **better and more accurate model**.

**Main Idea:**  
> “Many weak learners together form a strong learner.”  

---

## 8.2 Why Ensemble Learning is Needed

Single ML models may suffer from:

- High bias  
- High variance  
- Low accuracy  

**Benefits of Ensemble Learning:**

- ✔ Reduces errors  
- ✔ Improves accuracy  
- ✔ Increases stability  

---

## 8.3 Types of Ensemble Learning

Ensemble learning is mainly divided into three types:

- **Bagging (Bootstrap Aggregating)**  
- **Boosting**  
- **Stacking (Overview)**  

---

## 8.4 Bagging (Bootstrap Aggregating)

### 8.4.1 What is Bagging?

- Bagging trains **multiple models independently** using different subsets of data  
- Predictions are then combined  
- Each subset is created using **bootstrapping** (random sampling with replacement)  

### 8.4.2 How Bagging Works

1. Create multiple random samples from dataset  
2. Train a model on each sample  
3. Combine predictions (average or voting)  

### 8.4.3 Advantages of Bagging

- ✔ Reduces variance  
- ✔ Prevents overfitting  
- ✔ Works well with unstable models  

### 8.4.4 Limitations of Bagging

- ❌ Does not reduce bias  
- ❌ Requires more computation  

---

## 8.5 Random Forest

### 8.5.1 What is Random Forest?

- Random Forest is an **ensemble of Decision Trees**  
- Uses **bagging** and **random feature selection**  

### 8.5.2 How Random Forest Works

1. Create many decision trees  
2. Each tree is trained on random data and features  
3. Final output:  
   - Majority voting (classification)  
   - Average (regression)  

### 8.5.3 Advantages of Random Forest

- ✔ High accuracy  
- ✔ Handles missing values  
- ✔ Less overfitting than decision tree  

### 8.5.4 Limitations of Random Forest

- ❌ Less interpretable  
- ❌ Slower than single tree  

---

## 8.6 Boosting

### 8.6.1 What is Boosting?

- Boosting trains models **sequentially**, each focusing on previous errors  
- Converts **weak learners into strong learners**  

### 8.6.2 How Boosting Works

1. Train initial model  
2. Identify misclassified points  
3. Give more weight to errors  
4. Train next model  
5. Repeat process  

### 8.6.3 Types of Boosting

- **AdaBoost (Adaptive Boosting)** – Adjusts weights of incorrectly classified data; simple and effective  
- **Gradient Boosting** – Uses gradient descent to minimize loss; works for regression and classification  
- **XGBoost** – Optimized version of Gradient Boosting; fast, efficient, widely used  

---

## 8.7 Stacking (Overview)

- Combines predictions of multiple models  
- Uses another model (**meta-learner**) to make final prediction  
- Advanced technique (concept only)  

---

## 8.8 Comparison: Bagging vs Boosting

| Feature       | Bagging            | Boosting         |
|---------------|------------------|----------------|
| Training      | Parallel          | Sequential     |
| Focus         | Reduce variance   | Reduce bias    |
| Data weighting| Equal             | Weighted       |
| Example       | Random Forest     | AdaBoost       |

---

## 8.9 Advantages of Ensemble Learning

- ✔ Higher accuracy  
- ✔ Better generalization  
- ✔ Reduced overfitting  

---

## 8.10 Limitations of Ensemble Learning

- ❌ Complex models  
- ❌ High computation cost  
- ❌ Harder to interpret  

---

## 🎯 Exam-Oriented Questions

1. What is ensemble learning?  
2. Why is ensemble learning needed?  
3. Explain bagging with example.  
4. What is Random Forest?  
5. Explain boosting.  
6. Differentiate between bagging and boosting.  
7. Write short notes on:  
   - AdaBoost  
   - Gradient Boosting  
   - XGBoost  