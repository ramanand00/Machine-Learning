# UNIT 3: Data Handling and Data Preprocessing

## 3.1 What is Data?

Data is a collection of facts, values, or observations used to gain information.  

**In Machine Learning, data is the fuel that trains models.**  

**Examples:**  
- Student marks  
- House prices  
- Medical records  
- Images, text, videos  

---

## 3.2 Types of Data

### 3.2.1 Structured Data

- Organized in rows and columns  
- Stored in databases or spreadsheets  

**Example:**  

| Name | Age | Marks |
|------|-----|-------|
| Ram  | 20  | 80    |

✔ Easy to analyze  
✔ Used in most ML models  

### 3.2.2 Unstructured Data

- No fixed format  
- Hard to analyze directly  

**Examples:**  
- Images  
- Audio  
- Videos  
- Social media text  

✔ Requires preprocessing  
✔ Used in Deep Learning  

---

## 3.3 Dataset and Features

- **Dataset:** A collection of related data  
- **Features:** Input variables (attributes/independent variables)  

**Example:**  

| Age | Height | Weight | Result |
|-----|--------|--------|--------|
| 20  | 160    | 55     | Pass   |

- Features → Age, Height, Weight  
- Label → Result  

---

## 3.4 Data Collection Methods

- Surveys and Questionnaires  
- Sensors and IoT devices  
- Web scraping  
- Databases  
- Public datasets (Kaggle, UCI ML Repository)  

---

## 3.5 Data Cleaning

Raw data is often dirty and cannot be used directly.  

### 3.5.1 Handling Missing Values

Missing values occur due to:  
- Data entry errors  
- Incomplete data  

**Common techniques:**  
- Remove rows with missing values  
- Fill with mean/median/mode  
- Use prediction methods  

### 3.5.2 Removing Duplicate Data

Duplicate data causes:  
- Bias  
- Incorrect predictions  

> Must be removed before training.  

---

## 3.6 Data Transformation

### 3.6.1 Normalization

- Scales values between 0 and 1  

**Formula:**  
`X_norm = (X - X_min) / (X_max - X_min)`  

✔ Used when features have different ranges  

### 3.6.2 Standardization

- Converts data to Mean = 0, SD = 1  

**Formula:**  
`Z = (X - Mean) / Standard Deviation`  

✔ Used in algorithms like SVM, KNN  

---

## 3.7 Feature Encoding

Machine Learning models cannot understand text, so it must be converted into numbers.  

### 3.7.1 Label Encoding

- Converts categories into numbers  

**Example:**  

| Color | Encoded |
|-------|---------|
| Red   | 0       |
| Blue  | 1       |

✔ Simple  
❌ Creates false order  

### 3.7.2 One-Hot Encoding

- Creates binary columns  

**Example:**  

| Red | Blue | Green |
|-----|------|-------|
| 1   | 0    | 0     |

✔ No order issue  
❌ Increases columns  

---

## 3.8 Feature Scaling

Feature scaling ensures all features contribute equally.  

**Why needed?**  
- Some features dominate others  
- Improves model performance  

---

## 3.9 Splitting the Dataset

Dataset is divided into:

### 3.9.1 Training Set

- Used to train the model  
- Usually 70–80% of data  

### 3.9.2 Testing Set

- Used to evaluate the model  
- Usually 20–30% of data  

### 3.9.3 Validation Set

- Used to tune model parameters  
- Optional but important  

---

## 3.10 Importance of Data Preprocessing

✔ Improves accuracy  
✔ Reduces errors  
✔ Makes algorithms efficient  
✔ Avoids biased results  

> Good data = Good model  

---

## 3.11 Summary of UNIT 3

- Data is the foundation of ML  
- Data can be structured or unstructured  
- Cleaning and preprocessing are essential  
- Encoding converts text to numbers  
- Proper data splitting avoids overfitting  

---

## 🎯 Exam-Oriented Questions

1. What is data preprocessing?  
2. Explain structured and unstructured data.  
3. What are features and labels?  
4. Difference between normalization and standardization.  
5. Explain label encoding and one-hot encoding.  
6. Why is dataset splitting important?  