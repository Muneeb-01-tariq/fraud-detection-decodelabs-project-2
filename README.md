# fraud-detection-decodelabs-project-2
# 💳 Fraud Detection Pipeline using Machine Learning

## 📌 Project Overview

This project builds a machine learning pipeline to detect fraudulent credit card transactions. Since fraud cases are extremely rare compared to normal transactions, the dataset is highly imbalanced. To address this issue, the project uses **SMOTE (Synthetic Minority Oversampling Technique)** to balance the training data before training the models.

Two supervised machine learning algorithms were implemented and compared:

- Logistic Regression
- Random Forest Classifier

The models were evaluated using metrics that are more suitable for imbalanced datasets, including Precision, Recall, F1-Score, and ROC-AUC.

---

## 🎯 Objectives

- Understand and explore the credit card fraud dataset.
- Handle class imbalance using SMOTE.
- Train multiple machine learning models.
- Compare model performance.
- Evaluate models using appropriate metrics for fraud detection.

---

## 📂 Dataset

**Dataset:** Credit Card Fraud Detection

The dataset contains anonymized credit card transactions with the following features:

- Time
- V1 – V28 (PCA transformed features)
- Amount
- Class
  - 0 = Normal Transaction
  - 1 = Fraudulent Transaction

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## 📊 Project Workflow

1. Import required libraries
2. Load the dataset
3. Explore and understand the data
4. Check class imbalance
5. Split features and target
6. Perform train-test split
7. Apply SMOTE to balance the training data
8. Train Logistic Regression model
9. Train Random Forest model
10. Evaluate both models
11. Plot Confusion Matrix
12. Calculate ROC-AUC Score
13. Compare model performance

---

## 🤖 Machine Learning Models

### Logistic Regression

- Baseline classification model
- Easy to interpret
- Used for comparison

### Random Forest Classifier

- Ensemble learning algorithm
- Handles complex relationships
- Better performance for fraud detection

---

## 📈 Evaluation Metrics

The following metrics were used instead of Accuracy because the dataset is highly imbalanced:

- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## 📌 Results

- The dataset contained significantly more normal transactions than fraudulent ones.
- SMOTE successfully balanced the training dataset.
- Random Forest achieved better fraud detection performance than Logistic Regression.
- Recall and ROC-AUC were the most important evaluation metrics for this project.

---

## 📁 Repository Structure

```
Fraud-Detection-Pipeline/
│
├── Project2_Fraud_Detection.ipynb
├── creditcard.csv
├── README.md
```

---

## 🚀 How to Run

1. Clone this repository.

```
git clone https://github.com/your-username/Fraud-Detection-Pipeline.git
```

2. Install the required libraries.

```
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

3. Open the notebook.

```
Project2_Fraud_Detection.ipynb
```

4. Run all cells.

---

## 📷 Output

The notebook includes:

- Data Exploration
- Fraud Distribution Visualization
- SMOTE Balancing
- Logistic Regression Results
- Random Forest Results
- Confusion Matrix
- ROC Curve
- Model Comparison

---

## 📚 Learning Outcomes

Through this project, I learned:

- Data preprocessing
- Handling imbalanced datasets
- SMOTE oversampling
- Supervised machine learning
- Model evaluation techniques
- Fraud detection using machine learning

---

## 👨‍💻 Author

**Muhammad Muneeb Tariq**

BS Data Science Student

---

## ⭐ If you found this project helpful, consider giving it a Star!
