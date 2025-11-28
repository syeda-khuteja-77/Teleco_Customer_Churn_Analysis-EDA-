# 📞 Telecom Customer Churn Analysis – EDA

A complete Exploratory Data Analysis (EDA) project on telecom customer churn data to identify why customers leave, which segments are most at risk, and what business actions can reduce churn.
This project includes data cleaning, preprocessing, visual exploration, summary insights, and business recommendations.

---

## 📂 **Project Overview**

This analysis explores customer demographics, service usage patterns, contract types, payment behavior, and their relationship with churn.
The goal is to extract actionable insights that help reduce the churn rate and improve customer retention.

---

## 🛠️ **Tech Stack**

* 🐍 **Python**
* 📓 **Google Colab**
* 📊 **Pandas, NumPy**
* 🎨 **Matplotlib, Seaborn**

---

## 📥 **Dataset**

The dataset used in this analysis is:
**`Customer Churn.csv`**

It includes customer-level information such as:

* Demographics (gender, senior citizen)
* Subscription details (tenure, contract type, payment methods)
* Service usage (internet service, online security, tech support, etc.)
* Churn status

---

## 🧹 **Data Cleaning & Preprocessing**

✔ Converted `TotalCharges` column into numeric format
✔ Handled missing values
✔ Removed duplicates
✔ Converted binary columns (0/1) into readable labels (Yes/No)
✔ Formatted columns for visualization and better interpretation

---

## 📊 **Exploratory Data Analysis (EDA)**

### 🔸 **1. Churn Overview**

* **26.54%** of customers have churned
* **73.46%** stayed
  ➡️ High churn indicates major retention challenges

---

### 🔸 **2. Gender**

* Churn rates are **almost identical** across genders
  ➡️ Gender does *not* significantly influence churn

---

### 🔸 **3. Senior Citizens**

* Senior citizens show a **much higher churn rate**
  ➡️ Major high-risk customer segment

---

### 🔸 **4. Tenure**

* Customers with **1–2 months** of tenure have the **highest churn percentage**
  ➡️ Early customer experience is a weakness
* Long-tenure customers churn much less

---

### 🔸 **5. Contract Type**

* **Month-to-month** customers churn the most
* **One-year** and **two-year** contracts have significantly lower churn
  ➡️ Lack of long-term commitment drives churn

---

### 🔸 **6. Internet Services & Add-Ons**

Customers without:

* Online Security
* Tech Support
* Device Protection

…show **higher churn percentages**
➡️ Missing add-on services increase dissatisfaction

---

### 🔸 **7. Payment Method**

* **Electronic Check** users have the **highest churn rate**
  ➡️ Payment friction increases customer loss
* Credit card & bank transfer users churn less

---

## 🎯 **Overall Churn-Risk Profile**

Customers most likely to churn:

* Senior Citizens
* Month-to-Month contract users
* Electronic Check payers
* Customers with 1–2 months tenure
* Internet users without security/support add-ons

---

## ⭐ **Business Recommendations**

### ✅ **1. Strengthen Early-Tenure Support**

* Onboarding assistance during first 60 days
* Trial add-ons and discounts
* Early satisfaction check-ins

### ✅ **2. Promote Long-Term Contracts**

* Discounts for 1-year or 2-year upgrades
* Loyalty benefits for renewals

### ✅ **3. Reduce Electronic Check Usage**

* Promote auto-payment options
* Incentivize customers to switch billing methods

### ✅ **4. Improve Senior Citizen Support**

* Simplified plans
* Dedicated helpdesk
* Special service bundles

### ✅ **5. Upsell Add-On Services**

* Online security & tech-support combo packs
* Discounted protection add-ons for internet customers


## 📌 **Conclusion**

The project highlights key churn drivers, including short tenure, month-to-month contracts, senior citizen status, electronic check payments, and lack of security/support services.
Improving customer experience, promoting long-term plans, strengthening support for vulnerable groups, and optimizing service reliability can significantly reduce the **26.54% churn rate**.
