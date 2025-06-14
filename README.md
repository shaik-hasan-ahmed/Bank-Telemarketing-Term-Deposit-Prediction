# 📈 Bank Term Deposit Prediction - Telemarketing Optimization

This project applies machine learning to optimize telemarketing campaigns for a Portuguese retail bank by predicting customer subscription to term deposits. The goal is to improve marketing effectiveness, reduce unnecessary calls, and increase campaign ROI.

---

## 🧠 Project Overview

A **Decision Tree Classifier** was developed to predict whether a customer would subscribe to a term deposit offer based on demographic, financial, and campaign-related data.

Key tasks included:
- Data preprocessing & cleaning
- Feature encoding & scaling
- Handling severe class imbalance with **SMOTE**
- Exploratory Data Analysis (EDA)
- Model training & evaluation with multiple metrics
- Feature importance analysis for interpretability

---

## 📊 Results

- **Accuracy**: 76.4%  
- **Recall (Subscribed Class)**: 87.8%  
- **Precision**: 30.7%  
- **F1 Score**: 45.5%  
- **ROC-AUC**: 87.3%

These results show that the model is highly effective at identifying potential subscribers, even in the presence of imbalanced data.

---

## 📌 Key Features

- **Model:** Decision Tree Classifier (interpretable & modular)
- **Resampling:** SMOTE (to address class imbalance)
- **EDA Highlights:**  
  - Call duration strongly correlated with subscription  
  - Cellular contact methods more effective  
  - Previous successful campaigns increased likelihood of subscription  
- **Feature Importance:** Visualized to identify top predictive variables

---

## 🛠 Tech Stack

- **Language:** Python  
- **Libraries:** pandas, scikit-learn, imbalanced-learn, matplotlib, seaborn  
- **Deployment Ready:** Can be converted into a web app using Streamlit or Flask

---

## 🚀 Future Work

- Experiment with **ensemble models** (Random Forest, XGBoost)
- Apply **cost-sensitive learning** for better ROI optimization
- Explore **real-time prediction systems** for live marketing campaigns

---

## 📁 Dataset

- Source: )
- Merged from multiple `.csv` files with consistent features (~86,000 records)

---

## 👥 Contributors

- Hasan Ahmed Shaik  
- Venkata Subba Rao Are  
- Shoaib Mohammed  
- Nikhila Veera Chandini Pothula

---

## 📬 Contact

For questions or collaborations, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/hasanahmeds/) or open an issue.

