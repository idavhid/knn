# k-Nearest Neighbors (kNN) with Nested Cross-Validation

This repository contains a Jupyter Notebook that demonstrates the implementation of the k-nearest neighbors (kNN) algorithm along with nested cross-validation for robust model evaluation. In addition, the notebook includes code to calculate standard evaluation metrics and to visualize performance through a **confusion matrix**.
Written in 2020

## Key Features

- **Custom kNN Implementation**
  - Written from scratch using only Python built-in data structures (lists and dictionaries).
  - Provides a transparent, step-by-step look at how the kNN algorithm works under the hood.

- **Nested Cross-Validation**
  - Employs an **inner loop** for hyperparameter tuning (e.g., choosing the optimal value of *k*).
  - Uses an **outer loop** to estimate the generalization performance, reducing bias in model evaluation.
  - Implemented with **NumPy** arrays for efficiency.

- **Evaluation Metrics**
  - Accuracy, precision, recall, F1-score.
  - Support for multi-class problems.

- **Confusion Matrix**
  - Computed and displayed using NumPy arrays.
  - Offers an intuitive breakdown of classification results.

