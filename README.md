# Support Vector Machine (SVM) Projects

This repository contains implementations of **Support Vector Machine (SVM)** algorithms as part of a machine learning project portfolio. The goal of this repository is to understand how SVM works with different kernels and how it can be applied to various classification problems.

The projects include practical implementations of **Linear SVM**, **Kernel SVM**, and **RBF (Radial Basis Function) SVM**, along with dataset-based experimentation.

---

## 📌 Repository Contents

This repository is organized into multiple SVM-based mini projects:

### 1. Linear SVM

Implementation of **Linear Support Vector Machine**, used for linearly separable data.

Key concepts demonstrated:

* Hyperplane and margin maximization
* Support vectors
* Linear decision boundary
* Hard margin vs Soft margin

Dataset used:

* CC GENERAL dataset (`CC GENERAL.csv`)

---

### 2. Kernel SVM

Implementation of **Kernel SVM**, which allows SVM to classify non-linearly separable data by transforming it into higher dimensions.

Key concepts demonstrated:

* Kernel trick
* Non-linear decision boundaries
* Feature transformation
* Handling complex datasets

Dataset used:

* Heart disease dataset (`heart.csv`)

---

### 3. RBF SVM (Radial Basis Function Kernel)

Implementation of **RBF Kernel SVM**, one of the most commonly used SVM variants for non-linear classification.

Key concepts demonstrated:

* RBF (Gaussian) kernel
* Gamma parameter tuning
* Non-linear classification
* Model flexibility and overfitting control

Dataset used:

* Spam detection dataset (`spam.csv`)

---

## 🧠 Algorithms Covered

The repository includes the following SVM variants:

1. Linear SVM
2. Kernel SVM
3. RBF Kernel SVM

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 📁 Repository Structure

```
SVM-Projects/
│
├── Linear SVM/
│   ├── Linear_SVM.ipynb
│   └── CC GENERAL.csv
│
├── Kernel SVM/
│   ├── Kernel_SVM.ipynb
│   └── heart.csv
│
├── RBF SVM/
│   ├── RBF_SVM.ipynb
│   └── spam.csv
│
└── README.md
```

---

## 🎯 Learning Objectives

The objectives of this repository are:

* Understand the **working principles of SVM**
* Learn how **different kernels affect model performance**
* Explore **linear vs non-linear classification**
* Gain hands-on experience with **real-world datasets**
* Understand **hyperparameters like C and gamma**

---

## 🚀 Future Improvements

Planned enhancements for this repository include:

* Hyperparameter tuning using GridSearchCV
* Visualization of decision boundaries
* Comparison between different kernels
* Performance evaluation metrics (accuracy, precision, recall, F1-score)

---

## 👨‍💻 Author

**Supreet Raju**

This repository is part of a broader collection of machine learning mini projects covering regression, classification, and advanced algorithms.
