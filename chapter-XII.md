# UNIT 12: Computer Vision Basics

## 12.1 What is Computer Vision?

**Computer Vision (CV)** is a field of AI that enables computers to **see, analyze, and understand images or videos**, similar to human vision.

### Applications:

- Face recognition  
- Object detection  
- Autonomous vehicles  
- Medical image analysis  

---

## 12.2 Challenges in Computer Vision

- Variations in lighting and perspective  
- Occlusion (object partially hidden)  
- Complex backgrounds  
- Real-time processing constraints  
- High-dimensional image data  

---

## 12.3 Image Representation

Images must be represented as **numerical data** for ML models.

- **Grayscale Images** → 2D matrix of pixel intensities (0-255)  
- **Color Images (RGB)** → 3D matrix with channels (Red, Green, Blue)  

**Example:**  
Pixel (0,0) = [255, 128, 64] → RGB values

yaml
Copy code

---

## 12.4 Image Preprocessing Techniques

Before feeding images to a model, preprocessing is essential:

- **Resizing** – Standardize image size  
- **Normalization** – Scale pixel values (0-1)  
- **Grayscale Conversion** – Simplifies data  
- **Image Augmentation** – Rotate, flip, crop to create variations  

---

## 12.5 Feature Extraction in Computer Vision

Feature extraction identifies important patterns in images:

- **Edge Detection** – Detect boundaries of objects  
- **Corner Detection** – Identify key points in images  
- **Histogram of Oriented Gradients (HOG)** – Shape descriptor  

> In Deep Learning, **CNNs automatically extract features**.

---

## 12.6 Convolutional Neural Networks (CNN)

CNNs are the most popular deep learning models for images.

### 12.6.1 CNN Architecture

- **Convolution Layer** – Detects features using filters  
- **Activation Function (ReLU)** – Adds non-linearity  
- **Pooling Layer** – Reduces image size (Max/Avg pooling)  
- **Fully Connected Layer** – Produces final output  

### 12.6.2 Advantages of CNNs

- ✅ Automatic feature extraction  
- ✅ High accuracy for images  
- ✅ Reduces need for manual preprocessing  

---

## 12.7 Applications of Computer Vision

- **Face Recognition** – Security and authentication  
- **Object Detection** – Autonomous cars, surveillance  
- **Medical Imaging** – Tumor detection in X-rays or MRI  
- **Handwriting Recognition** – OCR (Optical Character Recognition)  
- **Image Captioning** – Generate textual descriptions  

---

## 12.8 Advantages of Computer Vision

- ✅ Automates image/video analysis  
- ✅ Improves accuracy for repetitive tasks  
- ✅ Can work in real-time applications  

---

## 12.9 Limitations of Computer Vision

- ❌ Sensitive to lighting and angle variations  
- ❌ Requires large labeled datasets  
- ❌ High computational resources (GPU needed)  
- ❌ Hard to interpret complex models  

---

## 12.10 Summary of UNIT 12

- Computer Vision deals with **images and videos**  
- Images are represented as **numerical matrices**  
- **Preprocessing** and **feature extraction** improve performance  
- **CNNs** are the key deep learning models for image tasks  
- Applications include **face recognition, object detection, and medical imaging**  

---

## 🎯 Exam-Oriented Questions

1. Define Computer Vision.  
2. Explain image representation for ML.  
3. Name common image preprocessing techniques.  
4. What is a CNN and its architecture?  
5. List applications of Computer Vision.  
6. Explain advantages and limitations of Computer Vision.