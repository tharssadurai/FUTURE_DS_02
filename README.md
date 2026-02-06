# FUTURE_DS_02
# 🔁 Customer Retention & Churn Analysis (SaaS / Subscription Business)

## 🧠 Project Overview
This project analyzes **customer churn patterns, retention drivers, and customer lifetime trends**
for a **subscription-based SaaS business** using the **Telco Customer Churn dataset**.

The objective is to identify **why customers leave**, **who is at risk**, and **what actions businesses
can take to reduce churn and improve long-term revenue**.

The analysis combines **Exploratory Data Analysis (EDA)**, **cohort-based retention analysis**, and
**machine learning–driven churn risk insights**, mimicking real-world SaaS business analytics.

---

## 🎯 Project Goals
- Analyze overall **customer churn rate**
- Identify **high-risk customer segments**
- Study **customer lifetime (tenure) vs churn**
- Understand pricing impact on churn
- Evaluate contract types and service categories
- Provide **actionable business recommendations** to improve retention

---

## 🧰 Tech Stack
- **Language:** Python  
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Dataset:** Telco Customer Churn (Subscription / SaaS scenario)

---

## 📁 Dataset Description
**Dataset:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`

The dataset contains customer-level subscription and service details.

**Key Columns:**
- `tenure` – Customer lifetime (months)
- `Contract` – Month-to-month / One year / Two year
- `MonthlyCharges` – Monthly subscription cost
- `TotalCharges` – Lifetime customer value
- `InternetService` – DSL / Fiber / No Internet
- `Churn` – Customer churn status (Yes / No)

---

## 🧹 Data Preprocessing
- Converted `TotalCharges` to numeric format
- Removed missing values
- Encoded categorical variables using `LabelEncoder`
- Created **tenure-based cohorts**:
  - 0–6 months
  - 6–12 months
  - 1–2 years
  - 2+ years

---

## 📊 Analysis Performed

### 🔍 Exploratory Data Analysis (EDA)
- Overall churn distribution
- Churn by contract type
- Tenure vs churn patterns
- Monthly charges vs churn
- Segment-wise churn by internet service

### 🔁 Cohort Retention Analysis
- Tenure-based customer cohorts
- Retention heatmap visualization
- Early-stage vs long-term customer behavior

### 🤖 Machine Learning Preparation
- Label encoding of categorical features
- Train-test split (80/20)
- Feature importance analysis
- ROC curve & AUC evaluation (churn prediction readiness)

---

## 📈 Visualizations Included
- Churn distribution bar chart
- Churn by contract type
- Customer lifetime vs churn histogram
- Monthly charges vs churn boxplot
- Cohort retention heatmap
- Feature importance ranking
- ROC curve performance snapshot
- Integrated churn analysis dashboard

---

## 💡 Key Insights
1. **Month-to-month contracts show the highest churn**, indicating low customer commitment.
2. **Most churn occurs within the first year**, highlighting weak early-stage retention.
3. **Higher monthly charges increase churn risk**, showing price sensitivity.
4. **Long-term customers exhibit strong loyalty and retention**.
5. **Fiber internet users show higher churn**, suggesting service quality or value concerns.

---

## 🚀 Business Recommendations
- Encourage migration to **long-term contracts** with discounts or bundled benefits.
- Improve **onboarding and engagement during the first 6–12 months**.
- Offer **loyalty rewards** for long-term customers.
- Revisit **pricing strategies** for high-paying churn-prone users.
- Enhance **service quality and customer support**, especially for Fiber Internet users.

---

**##🔮 Future Enhancements**

Build a churn prediction model (XGBoost / Random Forest)
Add customer lifetime value (CLV) prediction
Deploy interactive dashboard using Streamlit
Automate churn alerts for high-risk customers

---

**##🏁 Conclusion**

This project identifies key churn drivers in subscription-based businesses.
Early-stage customers, short-term contracts, and high monthly charges pose the
highest churn risk.

By improving onboarding, encouraging long-term plans, optimizing pricing, and
enhancing service quality, businesses can significantly reduce churn and
increase revenue stability.

This project reflects real-world SaaS analytics and decision-making.

**👤 Author**

THARSSA D
