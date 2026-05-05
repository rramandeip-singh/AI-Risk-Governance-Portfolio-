# MNIST Handwritten Digit Classification

## Project Overview
This project focuses on classifying handwritten digits (0–9) using the MNIST dataset. Multiple machine learning models were trained and compared to evaluate their performance on image classification tasks.

The goal is to understand how different algorithms perform on high-dimensional image data and identify the best-performing model.

---

## Dataset Information
- Dataset: MNIST (from OpenML)
- Total Samples: 70,000
- Training Set: 60,000 images
- Test Set: 10,000 images
- Features: 784 (28×28 pixel images)

Each image is represented as a flattened vector of pixel intensities.

---

## Technologies Used
- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

---

## Workflow

### 1. Data Loading
- Dataset loaded using OpenML
- Extracted features (`X`) and labels (`y`)

### 2. Data Preprocessing
- Checked missing values (none found)
- Normalized data using MinMaxScaler (0 to 1 range)
- Split into training, validation, and test sets

### 3. Data Visualization
- Displayed sample handwritten digits
- Plotted:
  - Accuracy comparison
  - Precision–Recall curve
  - Confusion matrix

---

## Models Implemented

| Model                  | Accuracy |
|----------------------|----------|
| Logistic Regression  | ~92%     |
| Decision Tree        | ~87%     |
| Random Forest        | ~96.8%   |
| K-Nearest Neighbors  | ~96.5%   |
| Neural Network (MLP) | ~97.4%   |
| Support Vector Machine (SVM) | ~97.8% |

Best Performance: **SVM & Neural Network (~98%)** :contentReference[oaicite:0]{index=0}  

---

##  Key Results
- High accuracy achieved across multiple models
- SVM performed best due to effectiveness in high-dimensional space :contentReference[oaicite:1]{index=1}  
- Neural Networks also showed strong performance for image classification  

---

## Evaluation Metrics
- Accuracy Score
- Precision–Recall Curve
- Confusion Matrix
- Classification Report

