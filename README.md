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
- Electronic Check: 45.8% churn rate  
- Mailed Check: 18.7% churn rate  
- Bank Transfer (Auto): 16.7% churn rate  
- Credit Card (Auto): 15.2% churn rate  

**Insight:** Customers using automatic payment methods are less likely to churn than those using manual methods.

---

### 2. Behavioral Insight
Manual payment methods like Electronic and Mailed Checks are more prone to delays and errors, potentially leading to service disruptions and churn. Automated methods reduce friction and improve convenience—encouraging retention.

---

### 3. Churn vs Tenure
- Customers with a tenure of less than 12 months had the highest churn rate.
- Long-term customers were more likely to stay.

**Insight:** The first year is critical for retention. Poor onboarding or unresolved early issues often drive early churn.

---

### 4. Churn by Contract Type
- Month-to-month: ~43% churn rate  
- One-year contract: ~11%  
- Two-year contract: ~3%  

**Insight:** Long-term contracts significantly reduce churn likelihood.

---

### 5. Churn by Internet Service Type
- Fiber Optic users churned more than DSL users.
- Customers without internet service showed the least churn.

**Insight:** Dissatisfaction with high-speed internet could be a driver for churn among tech-savvy users.

---

### 6. Churn vs Monthly Charges
- High monthly charge customers (> ₹80 or similar value) had higher churn.
- However, long-term high-paying users were less likely to leave.

**Insight:** High pricing combined with month-to-month billing increases churn risk.

---

### 7. Impact of Add-On Services
- Customers without add-ons like Tech Support or Online Security churned more.
- These features seem to reflect higher customer engagement or satisfaction.

**Insight:** Add-on services may serve as a proxy for loyal or more invested customers.

---

### 8. Gender and Churn
- No major difference in churn between male and female customers.

**Insight:** Gender alone is not a useful churn predictor.

---

### 9. Senior Citizens and Churn
- Senior citizens had a higher churn rate than non-senior customers.

**Insight:** Age-related comfort with technology and pricing concerns may influence behavior.

---

### 10. Dependence on Multiple Services
- Customers using more services (e.g., Phone + Internet + Streaming) churned less.

**Insight:** Bundling services creates higher switching costs and customer stickiness.

---

## Strategic Implications

Payment method, tenure, contract type, and service bundling are actionable levers that can help reduce churn. For example:

- Offering discounts for auto-pay
- Promoting longer-term contracts
- Encouraging bundled services
- Targeting early-tenure customers with personalized support

These strategies not only improve retention but also enhance the LTV:CAC (lifetime value to acquisition cost) ratio, leading to better margins and growth.

---

## Recommendations

### 1. Encourage Auto-Pay Enrollment
- Provide 5% discounts or loyalty points for auto-pay users  
- Highlight uninterrupted service, no late fees  
- Offer seamless, one-click auto-pay setup during onboarding  

### 2. Launch Targeted Retention Campaigns
- Focus on manual payers like Electronic and Mailed Check users  
- Use behavioral nudges like: "90% of customers like you use Auto-Pay"  
- Personalize messages via email or app notifications  

### 3. Build Trust and Awareness
- Promote safety of auto-pay (e.g., "bank-level security")  
- Provide FAQs, tutorials, and testimonials  
- Make switching to auto-pay frictionless and intuitive  

---

## Root Cause Hypotheses

Manual payment users may churn more due to:
- **Friction:** Manual billing requires more effort, increasing missed payments  
- **Tech Comfort:** Some users may not be digitally savvy  
- **Awareness:** Limited knowledge about auto-pay options  
- **Trust Issues:** Concerns about storing payment data online  
- **Satisfaction:** Dissatisfied customers may avoid or delay payments  

---

## Conclusion

The analysis demonstrates strong patterns in churn behavior tied to payment method, contract length, internet service, tenure, and service bundling. These are modifiable factors that can guide customer retention strategies. By focusing on these variables, telecom providers can improve profitability, reduce churn, and enhance overall customer experience.

---

## Tools Used

- **Python**
  - Pandas and NumPy: For data manipulation
  - Matplotlib and Seaborn: For data visualization
  - Jupyter Notebook: For analysis and documentation



