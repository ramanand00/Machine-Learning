# UNIT 2: Prerequisites for Machine Learning

> Purpose: Build the foundations (math + Python) you need to understand and implement Machine Learning algorithms.

---

## How to read this page (Legend)

- 🧾 Note — conceptual guidance and important facts  
- 💡 Tip — helpful suggestions or best practices  
- ⚠️ Warning — common pitfalls to avoid  
- ``` ``` (fenced code block) — code or formatted data (always shown with a language tag when appropriate)  
- ▶ Output — expected output or behavior from the preceding code block  
- ✅ Example — a short, self-contained example to illustrate the idea

---

## Table of contents

1. [Mathematical Foundations](#21-mathematical-foundations-for-machine-learning)  
   - Linear algebra, probability, statistics, calculus  
2. [Programming Basics (Python)](#22-programming-basics-for-machine-learning-python)  
   - Syntax, control flow, functions, libraries, Jupyter  
3. [Exam-oriented questions](#exam-oriented-questions)

---

## 2.1 Mathematical Foundations for Machine Learning

Mathematics enables machines to represent, manipulate and reason about data.

### 2.1.1 Linear Algebra Basics

Linear algebra is central to ML for representing data, parameters and operations.

- Scalars — a single number (e.g., `5`, `-3`, `0.8`)  
- Vectors — a list of numbers (1-D array). Represent features: `x = [10, 20, 30]`  
- Matrices — 2-D arrays used for datasets, transformations, weights.

✅ Example — Matrix notation (use fenced blocks for clarity):
```text
Matrix A (2×3):
[1 2 3]
[4 5 6]
```

Tip: When you see code blocks with `numpy` examples, read them as executable Python (use the given language tag).

### 2.1.2 Matrix Operations

Important operations:
- Matrix addition / subtraction
- Matrix multiplication (dot product)
- Transpose (Aᵀ)
- Inverse (A⁻¹) for square matrices (where defined)

✅ Example — NumPy usage:
```python
import numpy as np

A = np.array([[1, 2, 3],
              [4, 5, 6]])
B = A.T  # transpose
C = A.dot(B)  # matrix multiplication
```
▶ Output (shape info):
```text
A.shape -> (2, 3)
B.shape -> (3, 2)
C.shape -> (2, 2)
```

> Why important? ML algorithms rely on these for efficient vectorized computation.

---

### 2.1.3 Probability Basics

Probability helps quantify uncertainty.

- Probability = favorable outcomes / total outcomes  
- Key concepts: random experiment, event, sample space

✅ Example — coin toss:
```text
P(heads) = 1 / 2 = 0.5
```

Used in: Naive Bayes, probabilistic models, hypothesis testing.

---

### 2.1.4 Statistics Basics

Statistics summarizes and describes data.

- Mean (average): sum(values) / n  
- Variance: average squared deviation from mean  
- Standard deviation: sqrt(variance) — spread of data

✅ Example — formula-like illustration:
```text
mean = (x1 + x2 + ... + xn) / n
variance = sum((xi - mean)^2) / n
std_dev = sqrt(variance)
```

Tip: In code blocks labeled `python` you will usually see implementations with NumPy or Pandas.

---

### 2.1.5 Correlation and Covariance

- Covariance — indicates direction of joint variability between two variables  
- Correlation — normalized measure of the strength (range: -1 to 1)

Used for feature selection and exploratory data analysis.

---

### 2.1.6 Calculus Basics (Conceptual)

Calculus is used to find optima in ML models.

- Derivative — rate of change  
- Gradient — vector of partial derivatives (direction of steepest ascent/descent)

> Used in: Gradient Descent, optimization in neural networks.  
⚠️ Note: deep calculus is not required at first—understand concepts and how gradients are used.

---

## 2.2 Programming Basics for Machine Learning (Python)

Python is preferred for ML because it's simple, powerful, and has a rich ecosystem.

### 2.2.1 Introduction to Python

Python is a high-level, interpreted language used for data analysis and ML model building.

### 2.2.2 Variables and Data Types

- Variables store values:
```python
x = 10
name = "ML"
```

Common data types:
- `int` → `10`  
- `float` → `10.5`  
- `str` → `"Machine Learning"`  
- `bool` → `True` / `False`

### 2.2.3 Operators in Python

- Arithmetic: `+ - * /`  
- Comparison: `== != > <`  
- Logical: `and or not`

### 2.2.4 Conditional Statements

✅ Example:
```python
x = 5
if x > 0:
    print("Positive")
else:
    print("Negative or zero")
```
▶ Output:
```text
Positive
```

### 2.2.5 Loops

for loops and while loops:

```python
# for loop
for i in range(5):
    print(i)

# while loop
x = 0
while x < 3:
    print(x)
    x += 1
```
▶ Output:
```text
0
1
2
0
1
2
```

Tip: When reading loop examples, run them in a Jupyter cell to see output inline.

### 2.2.6 Functions

Functions make code reusable.

```python
def add(a, b):
    return a + b

print(add(2, 3))  # Output: 5
```

### 2.2.7 Python Libraries for Machine Learning (Introduction)

| Library       | Purpose                       |
|---------------|-------------------------------|
| NumPy         | Numerical computing, arrays   |
| Pandas        | Data structures and I/O       |
| Matplotlib    | Basic plotting / visualization|
| Scikit-Learn  | Classic ML algorithms         |

💡 Tip: Use `pip` or `conda` to install these (`pip install numpy pandas matplotlib scikit-learn`).

### 2.2.8 Jupyter Notebook

Jupyter Notebook is excellent for:
- Running code cells and visualizing outputs
- Mixing explanations (Markdown) with executable code
- Incremental experimentation

✅ Example cell structure:
- Markdown cell: explanation and equations  
- Code cell: implementation  
- Output cell: results, plots, tables

---

## 2.3 Importance of Unit 2 in Machine Learning

- Enables understanding of ML internals  
- Makes data handling and preprocessing easier  
- Improves problem solving and model building  
- Essential for practical ML projects

---

## 🎯 Exam-Oriented Questions

1. Why is mathematics important in Machine Learning?  
2. Explain the role of linear algebra in ML.  
3. What is the use of statistics in Machine Learning?  
4. Why is Python preferred for Machine Learning?

### Write short notes on:
- Mean and Standard Deviation  
- Gradient  
- Jupyter Notebook

---

## Suggested reading flow (how to study this page)

1. Read the conceptual subsections (Notes, Tips) to build intuition.  
2. Run the code blocks in a Jupyter Notebook to see outputs. Code blocks are fenced and tagged with language (e.g., `python`) — run those directly.  
3. Use the examples as templates: copy a code block into a new notebook cell, modify inputs, and observe changes.  
4. If you see a math formula, re-create it with NumPy to understand numeric behavior.

---

## Clean-up and fixes applied to this page

- Removed stray "markdown Copy code" artifacts and replaced them with proper fenced code blocks.  
- Standardized code formatting with language tags (e.g., `python`, `text`).  
- Added a "How to read this page" legend so readers instantly know how to treat blocks and callouts.  
- Included short runnable examples and expected outputs to lower friction for beginners.

---

If you want, I can:
- Convert this into a ready-to-commit file and open a PR to update the repository, or  
- Produce a printable PDF / more visually styled HTML version (with CSS) for distribution.

Tell me which next step you prefer and I will proceed.