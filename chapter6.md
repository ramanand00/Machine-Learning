# UNIT 6: Unsupervised Learning

## 6.1 Introduction to Unsupervised Learning

**Unsupervised Learning** is a type of Machine Learning where the model is trained using **unlabeled data**.

**The machine:**

- Does not know the output  
- Finds patterns, structures, and relationships on its own  

**Basic Idea:**  
> Input Data → Pattern Discovery → Grouping / Structure  

**Example:**

- Grouping customers by shopping behavior  
- Organizing news articles by topic  

---

## 6.2 Difference Between Supervised and Unsupervised Learning

| Feature | Supervised Learning | Unsupervised Learning |
|---------|-------------------|---------------------|
| Data    | Labeled           | Unlabeled           |
| Output  | Known             | Unknown             |
| Goal    | Prediction        | Pattern discovery   |
| Example | Spam detection    | Customer segmentation |

---

## 6.3 Clustering

### 6.3.1 What is Clustering?

- Process of **grouping similar data points** into clusters  

**Objects in the same cluster:**

- Are more similar to each other  
- Less similar to objects in other clusters  

### 6.3.2 Applications of Clustering

- Customer segmentation  
- Image segmentation  
- Market analysis  
- Document clustering  

---

## 6.4 K-Means Clustering

### 6.4.1 What is K-Means?

- Most popular clustering algorithm  
- Groups data into **K clusters**, where K is predefined  

### 6.4.2 Steps of K-Means Algorithm

1. Choose number of clusters (K)  
2. Select K random centroids  
3. Assign each data point to nearest centroid  
4. Update centroids  
5. Repeat until convergence  

### 6.4.3 Advantages of K-Means

- ✔ Simple and fast  
- ✔ Easy to implement  

### 6.4.4 Limitations of K-Means

- ❌ Must choose K beforehand  
- ❌ Sensitive to outliers  
- ❌ Works poorly with non-spherical clusters  

---

## 6.5 Hierarchical Clustering

### 6.5.1 What is Hierarchical Clustering?

- Creates a **tree-like structure** called a **dendrogram**  

### 6.5.2 Types of Hierarchical Clustering

- **Agglomerative (Bottom-Up)**  
  - Each point starts as its own cluster  
  - Clusters are merged step-by-step  

- **Divisive (Top-Down)**  
  - All data in one cluster  
  - Clusters are split step-by-step  

### 6.5.3 Advantages and Limitations

- ✔ No need to choose number of clusters initially  
- ❌ Computationally expensive  

---

## 6.6 Dimensionality Reduction

### 6.6.1 What is Dimensionality Reduction?

- Reduces the number of input features while keeping **important information**  
- Used when data has too many features  

### 6.6.2 Why Dimensionality Reduction is Needed

- ✔ Reduces computation  
- ✔ Avoids overfitting  
- ✔ Improves visualization  

---

## 6.7 Principal Component Analysis (PCA)

### 6.7.1 What is PCA?

- Popular **dimensionality reduction technique**  
- Converts features into **principal components**  
- Keeps **maximum variance**  

### 6.7.2 Applications of PCA

- Data visualization  
- Noise reduction  
- Feature compression  

---

## 6.8 Association Rule Learning (Overview)

- Finds **relationships between variables** in large datasets  

**Example:** Market basket analysis  
> “If a customer buys bread, they also buy butter”  

### 6.8.1 Key Terms

- Support  
- Confidence  
- Lift  

> (Concept level only for beginners)  

---

## 6.9 Advantages of Unsupervised Learning

- ✔ No labeled data required  
- ✔ Discovers hidden patterns  
- ✔ Useful for exploratory analysis  

---

## 6.10 Limitations of Unsupervised Learning

- ❌ Results are harder to evaluate  
- ❌ Less accurate than supervised learning  
- ❌ Interpretation is difficult  

---

## 🎯 Exam-Oriented Questions

1. Define unsupervised learning.  
2. Differentiate between supervised and unsupervised learning.  
3. Explain K-Means clustering with steps.  
4. What is hierarchical clustering?  
5. What is dimensionality reduction?  
6. Explain PCA.  
7. Write applications of clustering.  