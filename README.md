# Random-Forest
# 🌳 Decision Tree vs 🌲 Random Forest: A Comparative Analysis

Welcome to this repository! Here, we dive into a hands-on comparison between two powerful machine learning algorithms: **Decision Tree** and **Random Forest**. Whether you're exploring model interpretability or optimizing for performance, this guide will help you understand the strengths and trade-offs of each.

---

## 📁 Project Structure


---

## 🔍 Overview

| Feature               | Decision Tree 🌳            | Random Forest 🌲               |
|----------------------|-----------------------------|-------------------------------|
| **Type**             | Single model                | Ensemble of trees             |
| **Interpretability** | High                        | Moderate                      |
| **Overfitting Risk** | High                        | Lower (due to averaging)      |
| **Training Time**    | Fast                        | Slower                        |
| **Accuracy**         | May vary                    | Generally higher              |
| **Use Case**         | Quick insights, small data  | Robust predictions, large data|

---

## 📊 Evaluation Metrics

We used the following metrics to compare both models:

- ✅ Accuracy
- 📉 Precision, Recall, F1 Score
- 📈 ROC-AUC
- 🧪 Confusion Matrix

All metrics were computed using `scikit-learn` and visualized with `matplotlib` and `seaborn`.

---

## 🧠 Key Insights

- **Decision Tree** is great for interpretability and quick prototyping.
- **Random Forest** consistently outperforms in terms of generalization and robustness.
- Feature importance from Random Forest provides more stable insights across runs.

---

## 📸 Visual Comparison

![Decision Tree vs Random Forest](results/comparison_plot.png)

> *Above: Accuracy and F1 Score comparison across multiple runs.*

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/ML_GIT-Repo.git
cd ML_GIT-Repo

# Install dependencies
pip install -r requirements.txt

# Run models
python src/decision_tree.py
python src/random_forest.py

