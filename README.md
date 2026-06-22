# Iris Classification using Support Vector Machine (SVM)

## Project Overview

This project demonstrates the implementation of Support Vector Machine (SVM) classification using the Iris dataset. The objective is to classify Iris flowers into different species using both Linear and Radial Basis Function (RBF) kernels and compare their performance.

Support Vector Machine is a powerful supervised machine learning algorithm used for classification tasks. It works by finding the optimal hyperplane that best separates different classes.

---

## Dataset Information

### Dataset Source

Scikit-Learn Built-in Iris Dataset

### Dataset Size

* Total Samples: 150
* Total Features: 4
* Total Classes: 3

### Features

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

### Target Classes

* Setosa
* Versicolor
* Virginica

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Google Colab

---

## Project Workflow

### 1. Data Loading

The Iris dataset was loaded directly from the Scikit-Learn library.

### 2. Data Exploration

Performed dataset exploration using:

* DataFrame conversion
* Dataset information
* Statistical summary
* Target class analysis

### 3. Train-Test Split

The dataset was divided into:

* Training Data: 80%
* Testing Data: 20%

### 4. Linear Kernel SVM

A Support Vector Machine classifier was trained using a Linear Kernel.

### 5. RBF Kernel SVM

A Support Vector Machine classifier was trained using an RBF (Radial Basis Function) Kernel.

### 6. Model Evaluation

Performance was evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

### 7. Kernel Comparison

Both kernels were compared to determine which kernel produced better classification performance.

---

## Model Performance

### Linear Kernel Accuracy

(Replace with your actual result)

Example:

* Accuracy: 100%

### RBF Kernel Accuracy

(Replace with your actual result)

Example:

* Accuracy: 100%

---

## Kernel Comparison

A comparison was performed between:

* Linear Kernel
* RBF Kernel

The comparison helped analyze how kernel selection affects classification performance.

---

## Confusion Matrix

Confusion matrices were generated for both kernels to evaluate prediction performance and classification accuracy.

---

## Key Concepts Learned

* Support Vector Machine (SVM)
* Hyperplane
* Margin Maximization
* Kernel Functions
* Linear Kernel
* RBF Kernel
* Kernel Trick
* Classification Metrics
* Confusion Matrix

---

## Interview Questions

### What is a Hyperplane?

A hyperplane is a decision boundary that separates different classes in an SVM model. The objective of SVM is to find the optimal hyperplane that maximizes the margin between classes.

### What is the Kernel Trick?

The Kernel Trick allows SVM to handle non-linear data by transforming it into a higher-dimensional space where classes become linearly separable without explicitly computing the transformation.

### What is the difference between Linear and RBF Kernels?

* Linear Kernel is used when data is linearly separable.
* RBF Kernel is used when data is non-linear and requires more complex decision boundaries.

### Why is SVM effective?

SVM performs well in high-dimensional spaces and is effective when there is a clear margin of separation between classes.

---

## Deliverables

* Trained SVM Model
* Linear Kernel Results
* RBF Kernel Results
* Kernel Comparison Report
* Confusion Matrix
* Performance Evaluation

---

## Conclusion

Support Vector Machine (SVM) models were successfully implemented using both Linear and RBF kernels on the Iris dataset.

The models were trained and evaluated using accuracy score, classification report, and confusion matrix. Kernel comparison provided insights into the impact of kernel selection on classification performance.

This project demonstrates the practical application of SVM for multi-class classification and provides a strong understanding of hyperplanes, margins, and the kernel trick.

---

## Repository Structure

Task9-SVM-Iris-Classification/

├── Task9_SVM_Classification.ipynb

├── README.md

├── linear_kernel_result.png

├── rbf_kernel_result.png

├── kernel_comparison.png

---

## Author

Ankit Yadav

