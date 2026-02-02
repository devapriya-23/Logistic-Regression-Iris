# Logistic Regression from Scratch – Iris Dataset (Iris.py)

This project demonstrates a complete **Logistic Regression implementation from scratch using NumPy**, without relying on scikit-learn’s internal optimization.  
The model is trained and evaluated on the **Iris dataset** and compared directly with **scikit-learn’s LogisticRegression**.

---

## 📌 Project Overview

- **Dataset:** Iris
- **Classes Used:** Setosa (0) vs. Versicolor (1)
- **Features Used:**
  - Sepal Length
  - Petal Length
- **Optimization Method:** Gradient Descent
- **Loss Function:** Binary Cross-Entropy
- **Evaluation Metrics:** Accuracy, Precision, Recall

---

## 📂 Files

- **`Iris.py`**  
  A complete Python script that includes:
  - Dataset loading and preprocessing
  - Feature scaling using `StandardScaler`
  - Logistic Regression implemented from scratch with NumPy
  - Training using gradient descent
  - Model evaluation
  - Comparison with scikit-learn’s Logistic Regression

---

## ⚙️ Requirements

Install the required dependencies before running the script:

```bash
pip install numpy scikit-learn

---
▶️ How to Run

Execute the script using Python:

python Iris.py

---
The script will:

Load and preprocess the Iris dataset

Train a custom Logistic Regression model

Evaluate accuracy, precision, and recall

Train a scikit-learn Logistic Regression model

Print a comparison of results

📊 Model Performance
Custom Logistic Regression (From Scratch)

Accuracy: 1.0

Precision: 1.0

Recall: 1.0

Scikit-learn Logistic Regression

Accuracy: 1.0

Precision: 1.0

Recall: 1.0

Both models achieve perfect classification performance, indicating correct implementation and clear separability of the selected classes using the chosen features.

🧠 Learned Parameters

Weights:

Sepal Length: 0.960

Petal Length: 4.315

Bias: 0.957

Interpretation

Positive weights indicate that increasing feature values increases the probability of belonging to the positive class (Versicolor).

Petal length has a significantly larger coefficient, making it the strongest predictor.

The bias term shifts the decision boundary independently of the feature values.

✅ Key Takeaways

Logistic Regression can be successfully implemented from scratch using NumPy.

Gradient descent and binary cross-entropy loss are correctly applied.

The custom model matches scikit-learn’s performance, validating the implementation.

Petal length is the most influential feature for this classification task.

📜 License

This project is intended for educational and job-readiness purposes
