#  Customer Churn Analysis & Prediction

##  Project Overview

This project focuses on analyzing customer churn behavior and building a machine learning model to predict customers who are likely to leave a service. The goal is to identify key factors influencing churn and provide actionable business insights.

---

##  Objectives

* Analyze customer data to identify churn patterns
* Build a predictive model to classify churn vs non-churn customers
* Identify key drivers of churn using feature importance
* Create an interactive Power BI dashboard for business insights

---

##  Tools & Technologies

* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* **Scikit-learn** (Machine Learning)
* **Power BI** (Data Visualization)
* **Jupyter Notebook**

---

##  Dataset

* Telco Customer Churn Dataset
* Contains 7043 customer records with features like tenure, contract type, monthly charges, and internet service

---

##  Project Workflow

### 1. Data Cleaning

* Converted `TotalCharges` to numeric
* Handled missing values
* Removed irrelevant features like `customerID`

### 2. Exploratory Data Analysis (EDA)

* Analyzed churn distribution
* Identified key patterns:

  * High churn in month-to-month contracts
  * New customers churn more
  * Higher charges lead to higher churn

### 3. Model Building

* Used **Random Forest Classifier**
* Achieved ~79% accuracy
* Evaluated using precision, recall, and confusion matrix

### 4. Feature Importance

* Identified key factors:

  * Tenure
  * Monthly Charges
  * Total Charges

### 5. Power BI Dashboard

* Built interactive dashboard with:

  * KPI cards (Total Customers, Churn, Churn Rate)
  * Churn by Contract, Tenure, Charges
  * Filters for better analysis

---

##  Key Insights

* Customers with **month-to-month contracts** have highest churn
* **New customers (low tenure)** are more likely to churn
* **Higher monthly charges** increase churn probability
* **Fiber optic users** show higher churn behavior

---

##  Business Recommendations

* Promote long-term contracts
* Improve onboarding experience for new customers
* Offer incentives to high-risk customers
* Investigate service quality for high-churn segments

---

##  Model Performance

* Accuracy: ~79%
* Highlight: Model performs well overall but recall for churn can be improved

---

##  Challenges Faced

* Handling incorrect data types (`TotalCharges`)
* Avoiding wrong encoding of unique identifiers
* Managing Power BI cross-filtering issues
* Balancing model evaluation beyond accuracy

---

##  Future Improvements

* Hyperparameter tuning
* Handling class imbalance
* Trying advanced models (XGBoost)
* Deploying model using Streamlit

---

##  Conclusion

This project demonstrates an end-to-end data analysis workflow, combining Python and Power BI to generate actionable insights and support data-driven decision-making.

---

##  Author

Nagendra Jatav
