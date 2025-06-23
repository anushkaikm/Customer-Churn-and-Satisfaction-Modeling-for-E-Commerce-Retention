# Customer Churn and Satisfaction Prediction for E-Commerce

## 📌 Overview
This project develops a dual-model system to help e-commerce businesses proactively manage customer retention and experience. By predicting **customer churn** and **satisfaction levels**, the models provide strategic insights into user behavior, enabling data-driven marketing, service design, and loyalty initiatives.

The solution is built on real-world-style e-commerce data, combining thorough **exploratory analysis**, **feature engineering**, **hypothesis testing**, and **classification modeling**.

## 🎯 Objectives
- Predict which customers are at risk of churning using behavioral and demographic data.
- Classify customer satisfaction levels into **Low**, **Medium**, and **High**.
- Uncover key behavioral and service-level drivers influencing both churn and satisfaction.
- Deliver interpretable insights to support retention and customer experience strategies.

## 🧰 Tools & Technologies
- **Programming**: Python
- **Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Statsmodels, XGBoost, LightGBM
- **Techniques**: Classification Models, GridSearchCV, Cross-Validation, Threshold Tuning, Logistic Regression, Feature Importance Analysis, Hypothesis Testing

## 🔍 Project Highlights
- Achieved **91% F1-score** in churn prediction using a tuned **Random Forest** classifier.
- Classified customer satisfaction with **88% macro F1-score** using **LightGBM**.
- Performed end-to-end data processing: cleaning, encoding, standardization, and engineered features like `AvgOrderValue` and `CouponRedemptionRate`.
- Conducted thorough EDA (univariate, bivariate, multivariate) to extract behavioral and demographic patterns.
- Identified **complaints, tenure, cashback**, and **warehouse proximity** as key predictors of churn and satisfaction.

## 🧪 Methodology
1. **Data Cleaning**: Removed ~5% missing values, standardized categorical fields, and dropped duplicates.
2. **Feature Engineering**: Created derived variables to capture deeper behavior (e.g., engagement intensity, offer sensitivity).
3. **Exploratory Data Analysis (EDA)**: Used histograms, boxplots, heatmaps, and pairplots to analyze distributions and relationships.
4. **Hypothesis Testing**: Assessed if coupon usage impacts order value via logistic regression.
5. **Modeling**:
   - **Churn**: Logistic Regression, Random Forest, SVM
   - **Satisfaction**: Random Forest, LightGBM, XGBoost
6. **Model Tuning**: GridSearchCV and threshold optimization for class balance.
7. **Interpretation**: Visualized and explained top features influencing outcomes to support business strategy.

## 📈 Key Insights
- Complaints and short tenure strongly indicate churn risk.
- Delivery efficiency (`WarehouseToHome`) and high `AvgOrderValue` are top satisfaction drivers.
- Coupon usage alone does not significantly increase order value, challenging assumptions about promotion strategies.

## 🚀 Applications
- Early warning system for customer churn.
- Customer experience segmentation for loyalty and referral campaigns.
- Resource allocation strategies for customer service and logistics.
- Personalized marketing based on satisfaction and engagement profiles.

## 👩‍💻 Authors
- **Anushka Mondal** – Data Analyst, ML Engineer  
- **Rongxian [Last Name]** – Collaborator / Co-developer  

## 📝 License
This project is for academic use only. Contact the authors for permission to adapt or reuse the methodology for commercial applications.

---

