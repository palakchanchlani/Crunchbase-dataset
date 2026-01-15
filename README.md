# Crunchbase Startup Success Prediction 

## 📊 Project Overview
This project analyzes Crunchbase startup data to predict success/failure using machine learning models. It includes business insights, risk analysis, and hyperparameter tuning across multiple classifiers.

## 📁 Files Included
- `notebook.ipynb` → Full preprocessing, training, and evaluation pipeline  
- `crunchbase_model.pkl` → Saved best model (Voting Classifier: RF + XGBoost)  
- `report.pdf` → Internship report with diagrams and insights  
- `requirements.txt` → List of required Python libraries  

## ⚙️ Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- XGBoost  
- Voting Classifiers (multiple combinations)

## 🎯 Final Results
- Best tuned model: **Voting Classifier (RF + XGB)**  
- Test Accuracy: **95.13%**  
- Risk Insights: Funding (30%), Investors (25%), Industry/Network/Milestones (15% each)

## 📊 Visuals
- Accuracy bar chart: Before vs After tuning  
- Risk factor pie chart  
- Heatmap + Learning curve (Random Forest tuning)

