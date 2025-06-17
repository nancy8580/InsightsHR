# 🤖 Model Comparison Report

## 🎯 Models Tested:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

---

## 📊 Results Summary:

| Model              | Accuracy | Precision (Yes) | Recall (Yes) | F1-Score (Yes) |
|-------------------|----------|------------------|---------------|----------------|
| Logistic Regression| 86.73%   | 0.00             | 0.00          | 0.00           |
| Random Forest      | 83.33%   | 0.25             | 0.13          | 0.17           |
| XGBoost            | 80.27%   | 0.19             | 0.15          | 0.17           |
| Decision Tree      | 74.15%   | 0.20             | 0.31          | 0.24           |

---

## ✅ Insights:
- Random Forest performed best overall.
- Logistic Regression is easiest to interpret but less powerful.
- XGBoost is powerful and can be fine-tuned further.
- Tree-based models handle feature interactions better.

---

📁 Saved as `model_comparison.ipynb`  
📄 Markdown: `reports/model_comparison.md`