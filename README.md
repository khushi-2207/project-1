# 🍷 Wine Quality Prediction using Support Vector Machine (SVM)

This project predicts the **quality of white wine** based on its physicochemical properties using a **Support Vector Machine (SVM)** classifier.

---

## 🧠 Objective
The goal of this project is to analyze the **White Wine Quality dataset** and build a machine learning model that can predict wine quality (on a scale of 0–10) from its chemical composition.

---

## 📊 Dataset Information
**Source:** [UCI Machine Learning Repository – Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)  
**Number of Records:** 4898  
**Features:**
- Fixed Acidity  
- Volatile Acidity  
- Citric Acid  
- Residual Sugar  
- Chlorides  
- Free Sulfur Dioxide  
- Total Sulfur Dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  
- Quality (Target Variable)

---

## 🧩 Tools & Libraries Used
- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – Model training & evaluation (SVM, preprocessing)
- **Jupyter Notebook** – Implementation environment

---

## ⚙️ Project Workflow
1. **Data Loading:** Imported dataset from the YBI Foundation GitHub repository  
2. **Data Exploration:** Examined structure, summary statistics, and class distribution  
3. **Data Preprocessing:** Standardized feature values using `StandardScaler`  
4. **Model Training:** Built an SVM classifier to predict wine quality  
5. **Model Evaluation:** Evaluated accuracy, confusion matrix, and classification report  

---

## 📈 Model Results
- **Accuracy:** ~58%  
- The model performs best for mid-range wine qualities (5 and 6).  
- It struggles with extreme values due to **class imbalance**.  

### 🔍 Key Insights
- Wines with **higher alcohol** and **lower density** generally receive higher quality ratings.  
- SVM can serve as a good baseline model, but further tuning is required for optimal accuracy.

---

## 🚀 Future Improvements
- Perform **hyperparameter tuning** using `GridSearchCV`  
- Compare with **Random Forest** and **XGBoost** classifiers  
- Handle **class imbalance** using SMOTE or oversampling techniques  
- Build a simple **Power BI / Streamlit dashboard** for visualization

---

## 🏁 Conclusion
This project demonstrates a complete ML workflow — from data preprocessing and visualization to model training and evaluation — showcasing proficiency in **Python, ML, and data analysis**.

---

## 💻 Author
**Khushi Arora**  
📍 Data Analyst & ML Enthusiast  
🔗 [GitHub Profile](https://github.com/khushi-2207)  
🔗 [LinkedIn Profile](https://linkedin.com/in/khushi-0710s)
