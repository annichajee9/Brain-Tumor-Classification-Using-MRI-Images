# Brain-Tumor-Classification-Using-MRI-Images
This is my final project which is part of DAT402 at Arizona State University

The Brain Tumor Classification project focused on developing a machine learning model to classify MRI images of the human brain into different categories: glioma, meningioma, pituitary tumors, or no tumor. The goal was to create an automated diagnosis system that could assist medical professionals in identifying brain tumors at an early stage. The dataset used was obtained from Kaggle, containing labeled MRI images categorized by tumor type​.

## 🔧 Tools & Technologies Used:

### Programming Languages: Python
Libraries: OpenCV, TensorFlow, Keras, Matplotlib, Scikit-learn

### Machine Learning & Deep Learning Models:
Logistic Regression
Support Vector Machine (SVM)
Random Forest
Convolutional Neural Networks (CNNs) (best-performing model)

### Data Preprocessing:
Image augmentation (resizing, normalization)
Edge detection and segmentation
Feature extraction

## 📊 Results & Key Findings:
Different image resolutions were tested to find the optimal input size for classification:
100x100 pixels → Accuracy: 56%
256x256 pixels (Logistic Regression) → Accuracy: 78%
50x50 pixels (Random Forest) → Accuracy: 90% (Best model)​
The project emphasized the importance of model interpretability in medical applications. Misclassification in brain tumor diagnosis could lead to serious medical consequences, making model accuracy a critical factor​.

## Key insights included:
CNN models were the most effective for MRI classification.
Random Forest performed surprisingly well for lower-resolution images.
Proper data preprocessing significantly improved model performance.
