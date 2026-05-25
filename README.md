# 🧬 Liver Disorder Prediction using Machine Learning

## 📌 Overview
This project applies **machine learning techniques** to predict liver disorders based on patient health data. 
It demonstrates skills in **data preprocessing, feature engineering, model selection, and evaluation** — making it a strong portfolio piece for healthcare-focused ML applications.

## 📊 Dataset
- **Source:** UCI Liver Disorder Dataset (or specify if different)
- **Features:** Age, gender, biochemical measurements (bilirubin, alkaline phosphatase, SGPT, SGOT, etc.)
- **Target:** Classification of liver disorder presence

## ⚙️ Methodology
1. **Exploratory Data Analysis (EDA)** – Visualized distributions, correlations, and outliers  
2. **Data Preprocessing** – Handled missing values, scaling, and categorical encoding  
3. **Model Training** – Tested Logistic Regression, Random Forest, XGBoost  
4. **Evaluation** – Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC  

## 📈 Results
- Best performing model: **Random Forest** (Accuracy: 85%, F1-score: 0.83)  
- Key insight: Bilirubin and SGOT levels were strong predictors  

## 🛠️ Tech Stack
- **Python**  
- **Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn**  

## 💡 Use Cases
- Early detection support for medical practitioners  
- Educational resource for ML in healthcare  
pip install -r requirements.txt
python main.py
