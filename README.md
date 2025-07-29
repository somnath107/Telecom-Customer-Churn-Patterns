# Telecom Customer Churn Analysis

This project investigates customer churn behavior in a telecom company using Exploratory Data Analysis (EDA). The primary objective is to derive business insights that can help reduce customer churn and improve long-term profitability. A key area of focus is the impact of different payment methods on customer churn rates.

---

## Objective

The main goal of this project is to analyze patterns in customer churn and to understand how different customer attributes—especially payment methods—influence churn behavior. The outcome of the analysis is intended to inform strategies that telecom companies can use to increase customer retention and enhance customer lifetime value (CLTV).

---

## Dataset Overview

The dataset contains 7,043 records of telecom customers. Each entry provides multiple data points related to customer demographics, services subscribed, billing preferences, and churn status.

**Key attributes include:**
- Demographic information such as gender and senior citizen status  
- Service-related details such as internet service type and streaming options  
- Billing and payment details including monthly charges and payment method  
- Customer churn status indicating whether the customer stayed or left  

---

## Exploratory Data Analysis

The EDA process was structured into several steps to extract actionable insights:

- **Data Cleaning:** Handled missing values and encoded categorical variables to prepare the data.
- **Univariate Analysis:** Analyzed distribution of individual features such as churn, gender, and senior citizen status.
- **Bivariate Analysis:** Explored relationships between churn and other features like payment method and internet service.
- **Correlation Study:** Used correlation matrices and pairwise comparisons to identify significant numerical predictors of churn.
- **Data Visualization:** Created count plots, bar graphs, and box plots to visually highlight trends and anomalies.

---

## Key Findings

### 1. Churn Rate by Payment Method
- **Electronic Check:** 45.8% churn rate  
- **Mailed Check:** 18.7% churn rate  
- **Bank Transfer (Auto):** 16.7% churn rate  
- **Credit Card (Auto):** 15.2% churn rate  

**Insight:** Customers using automatic payment methods are less likely to churn than those using manual payment methods.

### 2. Behavioral Insight
Manual payment methods like Electronic and Mailed Checks are more prone to delays and errors, potentially leading to service disruptions and churn. Automated methods, on the other hand, reduce friction and improve convenience—encouraging customer retention.

---

## Strategic Implications

Payment method is a controllable factor that significantly influences churn. By encouraging automated payments, telecom companies can:

- Improve customer retention
- Boost customer lifetime value (CLTV)
- Lower customer acquisition cost (CAC)
- Enhance profitability

---

## Recommendations

### 1. Encourage Auto-Pay Enrollment
- Offer financial incentives (e.g., 5% discount or loyalty points)
- Highlight benefits like uninterrupted service and no late fees
- Simplify auto-pay setup during onboarding

### 2. Launch Targeted Retention Campaigns
- Focus on Electronic and Mailed Check users
- Send personalized nudges via email or in-app notifications
- Use behavioral cues: "90% of customers like you use Auto-Pay"

### 3. Build Trust and Awareness
- Include trust signals (e.g., "bank-level security")
- Use FAQs, tooltips, and tutorials to build awareness
- Make the transition process seamless and frictionless

---

## Root Cause Hypotheses

Manual payment users may churn more due to:

- **Friction:** Manual billing increases missed payments  
- **Tech Comfort:** Older users may resist digital automation  
- **Awareness:** Lack of knowledge about auto-pay benefits  
- **Trust Issues:** Hesitancy to store financial data online  
- **Satisfaction:** Dissatisfied users delay or avoid payments  

---

## Conclusion

The analysis reveals a strong link between payment methods and customer churn. Promoting automatic payments offers a strategic lever to reduce churn, enhance customer experience, and improve financial performance.

---

## Tools Used

- **Python**
  - Pandas and NumPy for data manipulation
  - Matplotlib and Seaborn for visualizations
  - Jupyter Notebook for documentation and interactivity




