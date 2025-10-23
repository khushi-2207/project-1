# 🍷 Wine Quality Prediction using Support Vector Machine (SVM)

This project predicts the **quality of white wine** based on its physicochemical properties using **Machine Learning (SVM)**.  
It demonstrates end-to-end data analysis, model building, and evaluation — progressing from **multi-class** to **binary classification** for improved accuracy.

---

## 🧠 Objective
To develop a predictive model that determines whether a wine is of **good** or **bad** quality based on its chemical composition.

---

## 📊 Dataset Information
**Source:** [UCI Machine Learning Repository – Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)  
**Records:** 4898  
**Features:** 11 independent chemical attributes  
**Target Variable:** Wine quality score (0–10)

---

## 🧩 Tools & Libraries Used
- **Python**
- **Pandas**, **NumPy** – Data preprocessing
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – Model training, scaling, and evaluation
- **Jupyter Notebook** – Code and results presentation

---

## ⚙️ Project Workflow

### **1. Data Import and Exploration**
- Loaded dataset using Pandas  
- Analyzed summary statistics and feature distributions  
- Visualized wine quality counts and feature correlations  

### **2. Data Preprocessing**
- Selected relevant independent variables  
- Scaled features using **StandardScaler** for uniformity  

### **3. Model 1 – Multi-Class SVM**
- Target variable: original 7-class labels (3–9)
- Accuracy: **68%**
- Limitations: lower precision for minority classes due to imbalance

### **4. Model 2 – Binary Classification SVM**
- Converted target variable into two classes:  
  - `0` → Poor quality (3, 4, 5)  
  - `1` → Good quality (6, 7, 8, 9)
- Accuracy improved to **88%**
- Model performs well for “good quality” wines (recall = 0.87)

### **5. Future Prediction Example**
- Randomly selected a new wine sample from dataset  
- Standardized features and predicted its quality class (`1` → good wine)

---

## 📈 Results Summary

| Model Type | Accuracy | Precision (Class 1) | Recall (Class 1) |
|-------------|-----------|---------------------|------------------|
| Multi-Class | 68% | 0.63 | 0.25 |
| Binary Class | **88%** | **0.81** | **0.87** |

✅ **Conclusion:**  
Binarizing the quality variable significantly improved accuracy and interpretability. The SVM model now classifies wine quality effectively for real-world use.

---

## 🔮 Future Improvements
- Hyperparameter tuning using **GridSearchCV**  
- Implement **Random Forest** and **XGBoost** for comparison  
- Apply **SMOTE** to balance minority classes  
- Build a simple **Power BI / Streamlit dashboard** for visualization

---

## 🏁 Key Learnings
- The importance of **feature scaling** for SVM performance  
- Handling **imbalanced datasets** improves predictive accuracy  
- Visualizations help uncover key correlations like *alcohol vs quality*

---

## 💻 Author
**Khushi Arora**  
📍 Data Analyst & ML Enthusiast  
🔗 [GitHub](https://github.com/khushi-2207)  
🔗 [LinkedIn](https://linkedin.com/in/khushi-0710s)
