
# 🎯 Logistic Regression: Credit Risk Classification

> A logistic regression model to assess **credit risk** for loan applicants based on financial and personal features.

---

## 📌 Project Highlights

- ✔️ Encoded categorical variables
- ✔️ Split the dataset into **training** and **testing** sets
- ✔️ Trained a **Logistic Regression** model
- ✔️ Evaluated model accuracy on both sets
- ✔️ Analyzed results using a **Confusion Matrix**

---

## 🧠 Tech Stack

- Python 🐍
- Pandas, NumPy
- Scikit-learn
- Matplotlib & Seaborn (for visualization)

---

## 📁 Files Overview

| File                  | Description                                |
|-----------------------|--------------------------------------------|
| `loan_data.csv`       | Raw dataset of loan applicants             |
| `credit_risk_model.ipynb` | Jupyter notebook with all steps from preprocessing to evaluation |
| `README.md`           | This documentation                        |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/credit-risk-logistic.git

# Navigate into the project directory
cd credit-risk-logistic

# Install dependencies
pip install -r requirements.txt
````

---

## 📊 Model Accuracy

| Dataset      | Accuracy |
| ------------ | -------- |
| Training Set | 89.7%    |
| Testing Set  | 86.4%    |

Confusion Matrix:

```
[[TN FP]
 [FN TP]]
```

> High true positives indicate the model’s strength in identifying **risky applicants** correctly.

---

## 🎨 Visuals

```python
# Confusion Matrix Heatmap
sns.heatmap(confusion_matrix(y_test, y_pred), annot=True, fmt='d', cmap='RdPu')
```

---

## 🧩 Key Learnings

* Logistic regression is powerful for **binary classification**
* Proper data preprocessing makes or breaks model performance
* Confusion matrices give more insight than just accuracy

---

## 🔗 Connect

Feel free to connect or fork this project if you're exploring **credit scoring, classification**, or just brushing up on **Logistic Regression fundamentals**.
