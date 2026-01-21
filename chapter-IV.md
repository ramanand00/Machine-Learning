# UNIT 4: Exploratory Data Analysis (EDA)

## 4.1 Introduction to Exploratory Data Analysis (EDA)

**Exploratory Data Analysis (EDA)** is the process of analyzing and understanding a dataset before applying Machine Learning models.

**Main purpose of EDA:**  
- Understand data structure  
- Find patterns and trends  
- Detect errors and outliers  
- Select important features  

**Key question:**  
> “What does my data look like?”  

---

## 4.2 Why EDA is Important in Machine Learning

EDA is important because:  

✔ Helps understand data distribution  
✔ Detects missing values and errors  
✔ Identifies relationships between variables  
✔ Improves model accuracy  
✔ Prevents wrong assumptions  

> Without EDA, ML models may fail or give wrong results.  

---

## 4.3 Descriptive Statistics

Descriptive statistics summarize the main characteristics of data.

### 4.3.1 Measures of Central Tendency

- **Mean:** Average value of data  
  `Mean = Sum of values / Total values`  
- **Median:** Middle value of sorted data  
  > Used when data has outliers  
- **Mode:** Most frequently occurring value  
  > Used for categorical data  

### 4.3.2 Measures of Dispersion

- **Range:** Difference between maximum and minimum values  
- **Variance:** Measures how far values are from the mean  
- **Standard Deviation (SD):** Square root of variance, shows data spread  
  - Low SD → Data is close to mean  
  - High SD → Data is spread out  

---

## 4.4 Data Visualization Basics

Data visualization helps understand data visually.

### 4.4.1 Types of Graphs Used in EDA

- **Histogram:** Shows data distribution, used to check skewness  
- **Bar Chart:** Used for categorical data  
- **Line Chart:** Shows trends over time  
- **Box Plot:** Shows data spread and outliers  
- **Scatter Plot:** Shows relationship between two variables, used to detect correlation  

---

## 4.5 Understanding Data Distribution

### 4.5.1 Normal Distribution

- Bell-shaped curve  
- Mean = Median = Mode  
> Many ML algorithms work best with normally distributed data  

### 4.5.2 Skewed Distribution

- **Right Skewed:** Long tail on right  
- **Left Skewed:** Long tail on left  
> Skewness affects model performance  

---

## 4.6 Relationship Between Variables

Understanding relationships helps in feature selection.

### 4.6.1 Correlation

Correlation measures the strength of relationship between variables.  

| Value | Meaning        |
|-------|----------------|
| +1    | Strong positive|
| 0     | No relation    |
| -1    | Strong negative|

> High correlation → Strong relationship  

### 4.6.2 Correlation Matrix

- Table showing correlation between multiple variables  
- Used to remove redundant features  

---

## 4.7 Outlier Detection

### 4.7.1 What are Outliers?

- Unusual or extreme values that differ significantly from other data points  
**Example:** Age = 200 years  

### 4.7.2 Why Remove Outliers?

❌ Can distort mean  
❌ Reduce model accuracy  
❌ Cause wrong predictions  

**Detected using:**  
- Box plot  
- Z-score  
- IQR method  

---

## 4.8 Feature Selection (Basic Concept)

Feature selection means choosing important features only.

**Benefits:**  
- Reduces overfitting  
- Improves performance  
- Reduces computation  

### 4.8.1 Types of Feature Selection

- Filter Method  
- Wrapper Method  
- Embedded Method  

> (Concept level for beginners)  

---

## 4.9 Steps in Exploratory Data Analysis

1. Understand the dataset  
2. Check missing values  
3. Analyze statistics  
4. Visualize data  
5. Detect outliers  
6. Identify relationships  
7. Select features  

---

## 4.10 Summary of UNIT 4

- EDA is used to explore data before modeling  
- Descriptive statistics summarize data  
- Visualization helps understand patterns  
- Correlation shows relationships  
- Outliers must be handled properly  
- Feature selection improves model quality  

---

## 🎯 Exam-Oriented Questions

1. What is Exploratory Data Analysis?  
2. Why is EDA important in Machine Learning?  
3. Explain mean, median, and mode.  
4. What is correlation? Why is it important?  
5. Explain outliers and their impact.  
6. List different data visualization techniques.  