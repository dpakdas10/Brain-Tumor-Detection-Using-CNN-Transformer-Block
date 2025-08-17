# 🧠 Brain Tumor Detection Using CNN + Transformer

## 📌 Overview
This project focuses on detecting brain tumors from MRI scans using a hybrid deep learning architecture that combines Convolutional Neural Networks (CNNs) and Transformer-based models.  
CNNs are used for feature extraction, while Transformers help capture long-range dependencies and contextual information in the images, improving classification accuracy.

## 🎯 Objective
To build an automated system that can accurately classify MRI brain images into tumor and non-tumor categories, aiding radiologists and healthcare professionals in early diagnosis and treatment planning.

## 🗂️ Dataset
The dataset consists of brain MRI images categorized into tumor and non-tumor classes.  
Images are preprocessed by resizing, normalizing pixel values, and applying data augmentation techniques like rotation and flipping.

**Dataset Source**: (Add source link or name here)  
**Number of Images**: 10,000  
**Classes**: Tumor, No Tumor

## ⚙️ Technologies Used
This project is built using the Python programming language.  
Deep learning frameworks used are TensorFlow or PyTorch.  
Other libraries include OpenCV for image processing and NumPy, Pandas for data handling.  
Matplotlib and Seaborn are used for visualizations.

## 📊 Model Performance

**CNN + Transformer Model**  
Accuracy: 99.46%  
Precision: 69.5%  
Recall: 80.0%  
F1-Score: 74.8%

**Random Forest**  
Accuracy: 80%  
Precision: 87%  
Recall: 84%  
F1-Score: 85%

**Support Vector Machine (SVM)**  
Accuracy: 85%  
Precision: 85%  
Recall: 95%  
F1-Score: 90%
