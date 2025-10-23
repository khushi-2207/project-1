# 🍷 Notebook Headings & Summaries for Wine Quality Project

## 🧮 9. Improving Model with Binary Classification
To handle class imbalance and simplify prediction, wine quality is re-labeled into **two categories**:
- **0 → Low Quality (3, 4, 5)**
- **1 → High Quality (6, 7, 8, 9)

This converts the problem into a **binary classification** task, allowing the SVM model to focus on separating good and bad wines more effectively.

## ⚙️ 10. Model Training (Binary SVM)
Re-trained the Support Vector Machine classifier with the new binary target variable.

## 📈 11. Model Evaluation (Binary Classification Results)
| Metric     | Class 0 | Class 1 |
|------------|---------|---------|
| Precision  | 0.70    | 0.81    |
| Recall     | 0.59    | 0.87    |
| F1-score   | 0.64    | 0.84    |

**Overall Accuracy: 88%**

The model performs strongly on predicting “good quality” wines (Class 1).

## 🔮 12. Future Prediction Example
Selected a random wine sample and predicted its quality class. The model successfully identified it as **good quality (1)**.

## 🏁 13. Conclusion
By transforming the multi-class problem into a binary classification task, the SVM model achieved significantly better accuracy (**88%**) and robustness.

This project demonstrates:
- Strong understanding of data preprocessing and scaling  
- Model optimization for class imbalance  
- Clear analytical reasoning and result interpretation
