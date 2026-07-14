# 📊 Customer Churn Prediction

🚀 End-to-end Machine Learning project to predict customer churn using telecom data.
This project analyzes customer behavior and builds predictive models to identify customers likely to leave, enabling proactive retention strategies.

---

## 📌 Project Overview

* Built a complete ML pipeline from **data cleaning → EDA → modeling → deployment**
* Identified key drivers of churn using statistical and visual analysis
* Implemented multiple ML models and selected the best-performing one
* Developed a reusable prediction system for real-world use cases

---

## 🧠 Problem Statement

Customer churn is a major challenge for telecom companies.
The goal of this project is to:

* Predict whether a customer will churn
* Identify key factors influencing churn
* Provide actionable business insights for retention

---

## 📂 Dataset

* Telecom Customer Dataset
* Includes:

  * Demographics
  * Account information
  * Service usage
  * Billing details

---

## 🔍 Exploratory Data Analysis (EDA)

Key findings:

* 📉 Customers with **low tenure** are more likely to churn
* 💰 Higher **monthly charges** increase churn probability
* 📄 **Month-to-month contracts** show highest churn rate
* ⚡ Customers using **electronic check payments** churn more

---

## ⚙️ Data Preprocessing

* Removed irrelevant features (`customerID`)
* Handled missing values in `TotalCharges`
* Encoded categorical variables using Label Encoding
* Addressed class imbalance using **SMOTE**

---

## 🤖 Model Building

Models trained:

* Decision Tree
* Random Forest ✅ *(Best Performing)*
* XGBoost

Techniques used:

* Train-Test Split
* Cross-validation (5-fold)
* Hyperparameter tuning

---

## 📊 Model Performance

* Evaluated using:

  * Accuracy
  * Precision
  * Recall
  * F1-score

✅ **Random Forest achieved the best performance**, effectively identifying churn customers.

---

## 💡 Business Insights

* High-risk churn customers:

  * Low tenure users
  * Month-to-month contracts
  * High monthly charges
* Recommended actions:

  * Offer long-term plans with discounts
  * Improve customer support services
  * Target high-risk users with retention campaigns

---

## 🚀 Deployment

* Saved model: `customer_churn_model.pkl`
* Saved encoders: `encoders.pkl`
* Built a prediction system that:

  * Accepts new customer data
  * Applies preprocessing
  * Predicts churn outcome

---

## 🛠️ Tech Stack

* **Programming:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost
* **Visualization:** Matplotlib, Seaborn
* **Modeling:** Machine Learning

---

## 📌 Key Highlights

* 📊 Performed detailed EDA to uncover churn patterns
* ⚖️ Solved class imbalance using SMOTE
* 🤖 Compared multiple ML models
* 📈 Delivered actionable business insights
* 🚀 Built a deployable prediction system

---

## 🔮 Future Improvements

* Deploy using Flask / FastAPI
* Add real-time prediction API
* Improve model performance using advanced techniques
* Integrate dashboard (Power BI / Streamlit)

---

## 👨‍💻 Author

**Pranay**
Aspiring Data Scientist | Data Analyst


