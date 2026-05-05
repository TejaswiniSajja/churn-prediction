# 📊 Customer Churn Prediction

This project predicts customer churn using machine learning techniques to help businesses identify customers likely to discontinue services and take proactive retention measures.

---

## 📌 Problem Statement  
Customer churn directly impacts business revenue. The objective of this project is to analyze customer behavior and build a predictive model to identify high-risk customers.

---

## ⚙️ Technologies Used  
- Python, Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (Logistic Regression, Decision Tree, Random Forest, SVM, Gradient Boosting, KNN)  

---

## 🧠 Machine Learning Workflow  

### 1. Data Cleaning & Preprocessing  
- Handled missing values using mean imputation  
- Encoded categorical variables and ensured data consistency  
- Checked for duplicates and validated dataset integrity  

### 2. Exploratory Data Analysis (EDA)  
- Analyzed feature correlations using heatmaps  
- Visualized churn distribution (imbalanced dataset)  
- Identified patterns based on customer usage and behavior  

### 3. Model Building  
- Trained multiple models:  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - Support Vector Machine (SVM)  
  - Gradient Boosting  
  - K-Nearest Neighbors (KNN)  
- Compared models to identify best-performing algorithm  

### 4. Evaluation  
- Metrics used: Accuracy, Precision, Recall, F1 Score, Confusion Matrix  
- Compared performance across models using visualization  

---

## 📈 Results  

- Random Forest achieved the best performance with **87.33% accuracy**  
- Gradient Boosting: **85.73% accuracy**  
- Decision Tree: **84.36% accuracy**  

### 📊 Key Insights  
- Dataset is imbalanced (Churn ≈ 17%, Non-Churn ≈ 83%)  
- Models achieved high accuracy but lower recall for churn class  
- Indicates difficulty in identifying churn customers accurately  

### 💡 Business Insights  
- Customers with shorter tenure are more likely to churn  
- Higher spending patterns show correlation with churn behavior  
- Model can help businesses identify high-risk customers and improve retention strategies  

---

## 📊 Dataset  
- File: `Churn_final_data.csv`  
- Contains customer demographics, usage data, and churn labels  
- Size: ~5630 rows × 20+ features *(update if exact known)*  

---

## 📂 Repository Structure  
- `Churn_pred.ipynb` → Full implementation (EDA, preprocessing, modeling)  
- `Churn_final_data.csv` → Dataset  
- `README.md` → Project documentation  

---

## 🚀 How to Run  

```bash
git clone https://github.com/TejaswiniSajja/churn-prediction.git
cd churn-prediction
