# 💳 Credit Card Fraud Detection using TensorFlow

## Overview

Credit card fraud has become a significant challenge for financial institutions due to the rapid growth of online transactions and digital payment systems. Detecting fraudulent transactions accurately is essential for reducing financial losses and improving customer trust.

This project presents a **deep learning solution** for credit card fraud detection using **TensorFlow** and **Keras**. A neural network was developed to classify transactions as either legitimate or fraudulent by learning patterns from historical transaction data. The project demonstrates the complete machine learning workflow, from data preprocessing to model evaluation and visualization.

---

## Project Objectives

- Develop a deep learning model for credit card fraud detection.
- Perform data preprocessing and feature scaling.
- Train and evaluate a TensorFlow neural network.
- Analyze model performance using multiple evaluation metrics.
- Visualize the learning process using accuracy and loss curves.

---

## Dataset

**Dataset:** Credit Card Fraud Detection

**Source:** Kaggle

### Dataset Information

- Total Transactions: **284,807**
- Features: **30**
- Target Variable:
  - **0** → Legitimate Transaction
  - **1** → Fraudulent Transaction

The dataset is highly imbalanced, making fraud detection a challenging binary classification problem.

---

## Technologies Used

- Python
- TensorFlow
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Project Workflow

- Import required libraries
- Load and explore the dataset
- Data preprocessing
- Feature scaling
- Train-test split
- Build the neural network
- Compile the model
- Train the model
- Evaluate the model
- Generate predictions
- Visualize model performance
- Save the trained model

---

## Neural Network Architecture

The model was developed using the **TensorFlow Keras Sequential API**.

Architecture:

- Input Layer
- Dense Layer (64 neurons, ReLU)
- Dropout Layer (30%)
- Dense Layer (32 neurons, ReLU)
- Dropout Layer (30%)
- Dense Layer (16 neurons, ReLU)
- Output Layer (1 neuron, Sigmoid)

**Optimizer:** Adam

**Loss Function:** Binary Cross-Entropy

**Evaluation Metric:** Accuracy

---

## Model Evaluation

The trained model was evaluated using several performance metrics, including:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

Training and validation accuracy and loss curves were also generated to assess the learning process and identify potential overfitting.

---

## Key Results

- Successfully built a TensorFlow-based deep learning model for binary classification.
- Achieved high testing accuracy on unseen transaction data.
- Training and validation accuracy remained closely aligned, indicating strong generalization.
- Training and validation loss decreased steadily and stabilized during training.
- The confusion matrix and classification report demonstrated effective fraud detection performance.

---

## Future Improvements

- Address class imbalance using SMOTE or class weights.
- Evaluate ROC-AUC and Precision-Recall AUC.
- Experiment with deeper neural network architectures.
- Deploy the model using Flask or FastAPI.

---

## Learning Outcomes

This project provided practical experience in:

- Deep Learning with TensorFlow
- Neural Network Design
- Data Preprocessing
- Feature Scaling
- Binary Classification
- Model Evaluation
- Performance Visualization
- End-to-End Machine Learning Workflow

---

## Author

**Rramandeip Singh**


---

⭐ If you found this project useful, feel free to star the repository.
