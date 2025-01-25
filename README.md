# Cancer_cell_classification
This repository contains a machine learning project where the Random Forest algorithm is used to classify cancer data. The project involves comparing multiple classification models, including Support Vector Machines (SVM), Gaussian Naïve Bayes (GaussianNB), and Random Forest, to identify the best-performing algorithm. Additionally, the Synthetic Minority Oversampling Technique (SMOTE) is used to address data imbalance.

**Project Overview**

**Objective**

The goal of this project is to classify cancer data effectively by testing different machine learning models and identifying the one with the highest accuracy. Random Forest was chosen based on its performance metrics, including accuracy and results from the confusion matrix.

**Dataset**

The dataset used in this project is the Breast Cancer dataset from the sklearn library. This dataset is a standard benchmark for binary classification problems.

**Methods Used**

1. Algorithms Tested:

Support Vector Machines (SVM)

Gaussian Naïve Bayes (GaussianNB)

Random Forest

2. Evaluation Metrics:

Accuracy

Confusion Matrix

3. Data Balancing:

SMOTE (Synthetic Minority Oversampling Technique) was used to handle data imbalance in the dataset.

**Results**

**Accuracy:** Random Forest achieved a slightly higher accuracy compared to SVM and GaussianNB.

**Confusion Matrix:** The confusion matrix of Random Forest indicates better classification performance, with fewer misclassifications.

**SMOTE Effectiveness:** After applying SMOTE, the model’s ability to classify minority class instances improved.

| Model         | Accuracy |
|---------------|----------|
| SVM           | 92.98    |
| GaussianNB    | 92.98    |
| Random Forest | **94.74**|
