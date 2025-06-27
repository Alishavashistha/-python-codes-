# Logistic Regression from Scratch

This project implements **Logistic Regression** manually using core Python libraries. The model is trained on synthetically generated binary classification data and optimized using gradient descent. This project is ideal for those looking to understand the inner workings of logistic regression beyond high-level machine learning libraries.

 📌 Project Overview

Logistic Regression is a fundamental algorithm used for binary classification. In this notebook, we:
- Generate a binary classification dataset
- Normalize input features
- Expand features using polynomial transformations
- Implement the sigmoid activation function
- Train the model using gradient descent
- Evaluate convergence using binary cross-entropy loss
- Visualize decision boundaries

This end-to-end implementation is done **without using scikit-learn's model classes**, offering hands-on insight into the logic and math behind classification models.

---

📁 Repository Contents

| File                          | Description                                                 |
|-------------------------------|-------------------------------------------------------------|
| logistic_regression.ipynb  | Jupyter Notebook implementing logistic regression from scratch |


🛠️ Libraries Used

- `numpy` – for vectorized numerical operations  
- `matplotlib` – for data visualization  
- `scikit-learn.datasets` – only used for synthetic data generation (`make_classification`)

🚀 Getting Started

To run this notebook:

 1. Clone the Repository
```bash
git clone https://github.com/Alishavashistha/ml-from-scratch.git
cd scratch
