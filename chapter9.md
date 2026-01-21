# UNIT 9: Introduction to Deep Learning

## 9.1 What is Deep Learning?

**Deep Learning (DL)** is a branch of Machine Learning that uses **artificial neural networks** to learn from large amounts of data.

**Key Points:**

- Can automatically extract features  
- Handles unstructured data (images, audio, text)  
- Learns complex patterns  

> 🔑 Deep Learning = Machine Learning + Neural Networks  

---

## 9.2 Difference Between Machine Learning and Deep Learning

| Feature            | Machine Learning        | Deep Learning                  |
|-------------------|------------------------|-------------------------------|
| Data Requirement   | Small to medium        | Large datasets                |
| Feature Extraction | Manual                 | Automatic                     |
| Hardware           | CPU                    | GPU preferred                 |
| Accuracy           | Moderate               | High (with enough data)       |
| Example            | Spam detection         | Face recognition, Self-driving cars |

---

## 9.3 Artificial Neural Networks (ANN)

### 9.3.1 What is an ANN?

- ANN is a **computational model inspired by human brain neurons**  
- Consists of layers of nodes (neurons) connected with weights  

### 9.3.2 Structure of Neural Network

- **Input Layer** – Receives input features  
- **Hidden Layers** – Process input and extract patterns  
- **Output Layer** – Produces prediction  

> Each neuron uses an **activation function** to introduce non-linearity.  

### 9.3.3 Activation Functions

| Function | Formula | Use |
|----------|--------|-----|
| Sigmoid  | 1 / (1 + e^-x) | Probabilities, binary output |
| ReLU     | max(0, x) | Hidden layers, avoids vanishing gradient |
| Tanh     | (e^x - e^-x) / (e^x + e^-x) | Output between -1 and 1 |

---

## 9.4 Training Neural Networks

Training uses **forward propagation** and **backpropagation**.

### 9.4.1 Forward Propagation

- Input → Hidden layers → Output  
- Compute predictions  
- Calculate error (loss function)  

### 9.4.2 Backpropagation

- Updates weights to reduce error  
- Uses **gradient descent** optimization  

---

## 9.5 Types of Deep Learning Networks

### 9.5.1 Feedforward Neural Network (FNN)

- Information moves forward only  
- Basic form of ANN  

### 9.5.2 Convolutional Neural Network (CNN)

- Designed for images and videos  
- Uses convolutional layers to extract features  

> **Example:** Face detection, image classification  

### 9.5.3 Recurrent Neural Network (RNN)

- Designed for sequential data (time series, text)  
- Maintains memory of previous inputs  

> **Example:** Language translation, speech recognition  

### 9.5.4 Long Short-Term Memory (LSTM)

- Type of RNN that solves long-term dependency problem  
- Remembers important past information  

---

## 9.6 Deep Learning Libraries

| Library      | Purpose                       |
|------------|-------------------------------|
| TensorFlow | Building DL models             |
| Keras      | High-level API for TensorFlow |
| PyTorch    | Research and production       |
| OpenCV     | Image and video processing    |

---

## 9.7 Advantages of Deep Learning

- ✔ Automatic feature extraction  
- ✔ Works well with unstructured data  
- ✔ High accuracy with large datasets  
- ✔ Handles complex patterns  

---

## 9.8 Limitations of Deep Learning

- ❌ Requires large datasets  
- ❌ Computationally expensive (GPU needed)  
- ❌ Harder to interpret  
- ❌ Longer training time  

---

## 9.9 Applications of Deep Learning

- Image recognition (CNN)  
- Speech recognition (RNN/LSTM)  
- Natural Language Processing (NLP)  
- Self-driving cars  
- Medical diagnosis (X-ray, MRI)  

---

## 9.10 Summary of UNIT 9

- Deep Learning is a subset of ML using **neural networks**  
- ANN has **input, hidden, and output layers**  
- Activation functions introduce **non-linearity**  
- CNN for **images**, RNN/LSTM for **sequential data**  
- Requires **large datasets** and **GPUs**  

---

## 🎯 Exam-Oriented Questions

1. Define Deep Learning.  
2. Difference between Machine Learning and Deep Learning.  
3. What is an Artificial Neural Network?  
4. Explain forward propagation and backpropagation.  
5. Write short notes on CNN and RNN.  
6. What are the advantages and limitations of Deep Learning?