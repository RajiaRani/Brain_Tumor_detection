# 🧠 Brain Tumor Detection using Convolutional Neural Networks (CNN)

## 📌 Project Overview
This project implements a **deep learning–based brain tumor detection system** using **Convolutional Neural Networks (CNNs)**.
The model analyzes **MRI brain scans** and classifies them into:

- Tumor
- Non-Tumor

The objective is to support **early diagnosis** by providing an automated, accurate image classification model.

---

## 🧠 Why CNN?
Convolutional Neural Networks are well suited for medical image analysis because they:
- Automatically extract spatial features from images
- Reduce manual feature engineering
- Perform efficiently on MRI scan data

---

## 📂 Dataset
- **Source:** Kaggle – Brain MRI Images for Brain Tumor Detection
- **Type:** MRI images
- **Classes:**
  - Tumor
  - No Tumor

Preprocessing steps include:
- Image resizing
- Normalization
- Label encoding

---

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- OpenCV / PIL
- Jupyter Notebook / Google Colab

---

## 🏗️ Model Architecture
The CNN architecture consists of:
- Convolutional layers for feature extraction
- MaxPooling layers for dimensionality reduction
- Flatten layer
- Fully connected (Dense) layers
- Sigmoid / Softmax output layer for classification

---

## 🔄 Workflow
1. Load MRI image dataset  
2. Preprocess images (resize, normalize)  
3. Encode labels (Tumor / Non-Tumor)  
4. Build CNN model  
5. Train the model  
6. Evaluate performance  
7. Predict on new MRI images  

---

## 📊 Results
- Achieved **high accuracy** on validation data
- Model effectively distinguishes tumor vs non-tumor MRI scans
- Performs well on unseen test images

> *Accuracy can be added here if available (e.g., 94%)*

---

## 🖼️ Sample Prediction
Input: MRI image  
Output:
- `Tumor Detected`
- `No Tumor Detected`

---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/your-username/brain-tumor-detection-cnn.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
