# 📘 Telecom Customer Churn Analysis

## 📊 Overview
This project analyzes customer churn behavior in a telecom company to identify key drivers behind customer attrition.  
Using Python, pandas, and visualization libraries, the project uncovers data-driven insights to help improve customer retention strategies.

---

## 🎯 Objective
- Identify factors influencing customer churn.
- Analyze customer demographics, service usage, and billing preferences.
- Provide actionable business insights and data-driven recommendations to reduce churn.

---

## 🧩 Dataset Information
**Dataset:** `Customer Churn.csv`  
**Records:** 7,043  
**Columns:** 21  

**Key Features:**
- **Demographics:** gender, SeniorCitizen, Partner, Dependents  
- **Services:** InternetService, OnlineSecurity, TechSupport, StreamingTV, StreamingMovies  
- **Account Info:** Contract, PaymentMethod, MonthlyCharges, TotalCharges, Churn  

---

## 🧹 Data Preprocessing
- Replaced blank values in `TotalCharges` with `0` and converted to float.  
- Recoded `SeniorCitizen` from (0/1) → ("No"/"Yes") for better readability.  
- Checked for missing values and duplicates (none found).  
- Validated data types for each feature.  

---

## 📈 Exploratory Data Analysis (EDA)
EDA was performed using **Matplotlib** and **Seaborn** to explore trends and relationships across customer attributes.

**Visualizations Included:**
- Churn distribution (bar & pie chart)  
- Demographic analysis (Gender, SeniorCitizen, Partner, Dependents)  
- Service feature impact (InternetService, Security, Backup, Tech Support)  
- Contract & billing analysis (Contract type, Payment method)  
- Tenure and charge correlations  

---

## 🔍 Key Findings

| Category | Observation | Metric |
|-----------|--------------|--------|
| **Overall Churn** | 1,869 out of 7,043 customers churned | **26.5%** |
| **Senior Citizens** | Higher churn vs non-seniors | **41.5% vs 23.6%** |
| **Contract Type** | Month-to-month customers churn most | **42.8% vs 2.7% (2-year)** |
| **Internet Service** | Fiber users have highest churn | **41% vs 19% (DSL)** |
| **Add-on Services** | Lack of TechSupport/OnlineSecurity increases churn | **2–2.5× higher** |
| **Payment Method** | Electronic check users churn more | **45.3%** |
| **Tenure** | Churned avg tenure = 18 mo; Retained = 38 mo | **−20 mo difference** |

---

## 💡 Business Recommendations
- Incentivize **annual and two-year contracts** to reduce short-term churn.  
- Improve **fiber optic service quality** and pricing transparency.  
- Offer **Tech Support and Security bundles** with internet plans.  
- Target **senior citizens** with affordable, simplified plans.  
- Encourage **auto-payment options** for smoother billing experience.  
- Introduce **onboarding and loyalty programs** during first 6 months.  

---

## 🧠 Skills Demonstrated
- **Data Cleaning & Wrangling:** pandas, numpy  
- **Exploratory Data Analysis (EDA):** matplotlib, seaborn  
- **Statistical Analysis:** correlation, distribution, trend interpretation  
- **Business Insight Generation:** data storytelling, recommendation framing  
- **Data Visualization:** custom plots, annotated bar charts, pie charts  
- **Python for Analytics:** feature handling, logic functions, automation  

---

## 🛠️ Tech Stack
- **Language:** Python 3.x  
- **Libraries:** pandas, numpy, matplotlib, seaborn  
- **Environment:** Jupyter Notebook / Google Colab  

---

## 📂 Project Structure

Telecom-Customer-Churn-Analysis/    
│    
├── Telecom-Customer_Churn_dataset_Analysis.ipynb    # Main EDA notebook    
├── Customer Churn.csv                               # Dataset    
├── README.md                                        # Project documentation    
└── 📊 Executive Summary – Telecom Customer Churn Analysis.pdf  # Optional visual exports  

---

## 🧭 Future Improvements

- Add predictive modeling (Logistic Regression, Random Forest) for churn prediction.
- Deploy a dashboard using Power BI or Tableau for interactive insights.
- Integrate churn alerts in a data pipeline for real-time monitoring.

---

## 📘 Project Impact

- Improved understanding of key churn drivers across demographics and services.
- Identified actionable areas to potentially reduce churn by 20–30%.
- Demonstrated strong analytical, visualization, and business storytelling skills.

---

## ✍️ Author

Aman Singh Negi    
📊 Data Analyst | Python | SQL | Visualization | EDA     
📧 Email: [theanalyst.aman@gmail.com]     
