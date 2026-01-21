# UNIT 7: Model Training and Optimization

## 7.1 What is Model Training?

Model training is the process of **teaching a machine learning algorithm to learn patterns from training data**.

**During training:**

- Input data is given to the model  
- Model makes predictions  
- Errors are calculated  
- Model parameters are updated  

> **Training Data → Model → Prediction → Error → Update**  

---

## 7.2 Training a Machine Learning Model

**Basic steps:**

1. Collect dataset  
2. Preprocess data  
3. Split dataset (train & test)  
4. Choose algorithm  
5. Train model  
6. Evaluate performance  
7. Improve model  

---

## 7.3 Overfitting and Underfitting

### 7.3.1 Underfitting

Occurs when the model is **too simple** and cannot learn patterns.

**Characteristics:**

- Poor training accuracy  
- Poor testing accuracy  

**Example:** Linear model for complex data  

### 7.3.2 Overfitting

Occurs when the model **learns noise instead of patterns**.

**Characteristics:**

- High training accuracy  
- Low testing accuracy  

**Example:** Very deep decision tree  

### 7.3.3 Perfect Fit

- Balanced learning  
- Good performance on new data  

---

## 7.4 Bias–Variance Tradeoff

| Term     | Meaning                            |
|----------|----------------------------------|
| Bias     | Error due to oversimplification   |
| Variance | Error due to sensitivity to data |

**Goal:** Balance bias and variance  

---

## 7.5 Cross-Validation

### 7.5.1 What is Cross-Validation?

Technique to **evaluate model performance more reliably**  

### 7.5.2 K-Fold Cross-Validation

**Steps:**

1. Split data into K parts  
2. Train on K-1 parts  
3. Test on remaining part  
4. Repeat K times  

**Advantages:**

- Uses data efficiently  
- Reduces overfitting risk  

---

## 7.6 Hyperparameter Tuning

### 7.6.1 What are Hyperparameters?

- Parameters set **before training**  
- Control learning process  

**Examples:** Learning rate, number of neighbors (K), tree depth  

### 7.6.2 Hyperparameter Tuning Methods

- **Grid Search**  
- **Random Search**  

**Goal:** Find best parameter values  

---

## 7.7 Regularization

### 7.7.1 What is Regularization?

- Prevents overfitting by **adding a penalty**  

### 7.7.2 L1 Regularization (Lasso)

- Adds **absolute value penalty**  
- Can eliminate features  
- 📌 Used for feature selection  

### 7.7.3 L2 Regularization (Ridge)

- Adds **squared penalty**  
- Shrinks coefficients  
- 📌 Improves generalization  

---

## 7.8 Learning Rate

- Controls **how fast a model learns**  
- Too high → Overshoot  
- Too low → Slow learning  

> Proper learning rate is important  

---

## 7.9 Early Stopping

- Stops training when performance stops improving  
- Prevents overfitting  
- Saves computation  

---

## 7.10 Model Evaluation and Improvement Cycle

**Train → Evaluate → Tune → Retrain → Test**  

---

## 7.11 Summary of UNIT 7

- Model training teaches patterns  
- Overfitting and underfitting affect performance  
- Bias-variance tradeoff must be balanced  
- Cross-validation improves reliability  
- Regularization controls model complexity  

---

## 🎯 Exam-Oriented Questions

1. What is model training?  
2. Define overfitting and underfitting.  
3. Explain bias-variance tradeoff.  
4. What is cross-validation?  
5. Explain K-fold cross-validation.  
6. What is regularization?  
7. Differentiate between L1 and L2 regularization.  
8. What is hyperparameter tuning?  