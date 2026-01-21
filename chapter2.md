# UNIT 2: Prerequisites for Machine Learning

Machine Learning requires some basic knowledge of:  

- Mathematics  
- Programming (Python)  

This unit builds the foundation needed to understand ML algorithms.

---

## 2.1 Mathematical Foundations for Machine Learning

Mathematics helps machines understand data, patterns, and relationships.

### 2.1.1 Linear Algebra Basics

Linear Algebra is used to represent and manipulate data.

- **Scalars:** A single number  
  Example: 5, -3, 0.8  

- **Vectors:** A list of numbers (1-D array)  
  Represent features  
  Example: `[10, 20, 30]`  

- **Matrices:** A collection of vectors (2-D array)  
  Used to store datasets  
  Example:  
[1 2 3]
[4 5 6]

markdown
Copy code

### 2.1.2 Matrix Operations

Important operations used in ML:  
- Matrix Addition  
- Matrix Subtraction  
- Matrix Multiplication  
- Transpose of Matrix  

> **Why important?** ML algorithms work internally using matrices for speed and efficiency.

### 2.1.3 Probability Basics

Probability measures uncertainty.  

**Probability Formula:**  
Probability = Favorable outcomes / Total outcomes

markdown
Copy code

**Key Concepts:**  
- Random Experiment  
- Event  
- Sample Space  

> **Used in:** Naive Bayes, Predictive models, Risk analysis  

### 2.1.4 Statistics Basics

Statistics helps in analyzing and summarizing data.

- **Mean (Average):** Sum of values / Number of values  
- **Variance:** Measures how far data points are from the mean  
- **Standard Deviation:** Square root of variance; measures data spread  

### 2.1.5 Correlation and Covariance

- **Correlation:** Strength of relationship between variables  
- **Covariance:** Direction of relationship  

> **Used in:** Feature selection and data analysis  

### 2.1.6 Calculus Basics (Conceptual)

Calculus is used to optimize ML models.

- **Derivative:** Measures rate of change  
- **Gradient:** Direction of steepest increase or decrease  

> **Used in:** Gradient Descent, Neural Networks  

⚠️ Note: Deep calculus is not required initially, only the concept.

---

## 2.2 Programming Basics for Machine Learning (Python)

Python is the most popular language for Machine Learning because it is:  

- Simple  
- Powerful  
- Has many ML libraries  

### 2.2.1 Introduction to Python

Python is a high-level, interpreted programming language.  

> **Used for:** Data analysis, ML model building, AI applications  

### 2.2.2 Variables and Data Types

- **Variables:** Used to store values  
x = 10
name = "ML"

markdown
Copy code

- **Common Data Types:**  
- int → 10  
- float → 10.5  
- string → "Machine Learning"  
- boolean → True / False  

### 2.2.3 Operators in Python

- **Arithmetic Operators:** `+ - * /`  
- **Comparison Operators:** `== != > <`  
- **Logical Operators:** `and or not`  

### 2.2.4 Conditional Statements

Used to make decisions.

```python
if x > 0:
  print("Positive")
else:
  print("Negative")
2.2.5 Loops
Used to repeat tasks.

for loop

python
Copy code
for i in range(5):
    print(i)
while loop

python
Copy code
while x < 5:
    print(x)
    x += 1
2.2.6 Functions
Functions make code reusable.

python
Copy code
def add(a, b):
    return a + b
2.2.7 Python Libraries for ML (Introduction)
Library	Purpose
NumPy	Mathematical operations
Pandas	Data handling
Matplotlib	Data visualization
Scikit-Learn	ML algorithms

2.2.8 Jupyter Notebook
Jupyter Notebook is used to:

Write Python code

Visualize output

Explain code step-by-step

Widely used by Data Scientists, ML Engineers, Students

2.3 Importance of Unit 2 in Machine Learning
Helps understand ML algorithms

Makes data handling easier

Improves problem-solving skills

Required for real-world ML projects

2.4 Summary of UNIT 2
Mathematics is the backbone of ML

Linear Algebra represents data

Probability & Statistics analyze uncertainty

Python is the primary language for ML

Libraries simplify ML implementation

🎯 Exam-Oriented Questions
Why is mathematics important in Machine Learning?

Explain the role of linear algebra in ML.

What is the use of statistics in Machine Learning?

Why is Python preferred for Machine Learning?

Write short notes on:

Mean and Standard Deviation

Gradient

Jupyter Notebook