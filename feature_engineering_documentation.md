# Feature Engineering Documentation

## Overview
Due to the limited number of raw features, feature engineering focused on transforming existing variables to extract more meaningful information relevant to churn behavior.

---

## Engineered Features

### 1. Average Monthly Spend
**Formula:**  
TotalCharges / (Tenure + 1)

**Rationale:**  
Represents long-term customer spending behavior.

---

### 2. High Spender Flag
**Formula:**  
MonthlyCharges > median(MonthlyCharges)

**Rationale:**  
Identifies customers with premium usage patterns.

---

### 3. Tenure Bucket
**Categories:**  
- Short  
- Medium  
- Long  

**Rationale:**  
Customer loyalty and churn risk vary with service duration.

---

### 4. Log Total Charges
**Formula:**  
log(1 + TotalCharges)

**Rationale:**  
Reduces skewness and stabilizes variance.

---

### 5. Charges Growth Rate
**Formula:**  
TotalCharges / (Tenure + 1)

**Rationale:**  
Captures spending growth relative to customer lifetime.

---

## Feature Selection
Feature importance was evaluated using Random Forest models.
Low-impact features were excluded to reduce noise and improve generalization.

---

## Business Interpretation
Customers with high charges, shorter tenure, and certain contract types were found to have a higher likelihood of churn.

---

## Conclusion
Feature engineering improved predictive capability while maintaining interpretability and alignment with business objectives.
