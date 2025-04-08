# personalized-insurance-pricing
A machine learning project focused on predicting personalized health insurance charges using demographic and lifestyle data. Techniques include linear regression, random forest, and XGBoost with performance evaluation and feature analysis.

# 💡 Predictive Analytics for Personalized Insurance Pricing

This project applies machine learning techniques to predict personalized health insurance charges using a dataset of demographic and lifestyle attributes. The goal is to build fair, accurate, and interpretable pricing models that could be adopted in real-world insurance systems.

## 📊 Project Overview
As part of my graduate studies in Industrial Engineering at the University at Buffalo, this project explores the use of advanced predictive modeling techniques to calculate personalized insurance charges based on features like:

- Age
- BMI
- Number of children
- Smoker status
- Region

## 🔧 Tools & Technologies
- **Languages:** Python
- **Libraries:** scikit-learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn
- **Techniques:** Linear Regression, Random Forest, XGBoost, Cross-validation, Feature Encoding

## 🧠 Key Insights
- **Smoker status** and **BMI** were the most impactful features affecting insurance cost.
- **XGBoost** delivered the highest accuracy (lowest RMSE and highest R² score), outperforming Random Forest and Linear Regression.
- Feature importance analysis confirmed industry expectations and provided interpretable insights.

## ⚙️ ML Pipeline
1. **Preprocessing** – Categorical encoding, scaling, handling skew
2. **Modeling** – Comparison between Linear Regression, Random Forest, and XGBoost
3. **Evaluation** – RMSE, R², residual plots, feature importance
4. **Insights** – XGBoost captured non-linear behavior effectively

## 📉 Performance Metrics

| Model            | RMSE    | R² Score |
|------------------|---------|----------|
| Linear Regression| 5796.28 | 0.78     |
| Random Forest    | 4567.96 | 0.87     |
| XGBoost          | 4517.29 | 0.87     |


## 🔍 Future Work
- Use SHAP values for better model explainability
- Integrate real-time data from wearables
- Implement fairness-aware ML techniques
