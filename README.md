# Customer Churn Analysis in Subscription-Based Telecommunications Services

## Dissertation Title
**Impact of Service Quality and Pricing on Customer Churn in Subscription-Based Services:  
The Role of Customer Engagement**

---

## Project Overview
This repository documents the complete analytical workflow used in the MSc dissertation that investigates customer churn in the telecommunications industry. The study focuses on understanding how service quality and pricing influence customer churn and examines the role of customer engagement using quantitative business analytics techniques.

The analysis is based on a large-scale customer-level dataset and applies descriptive statistics, correlation analysis, logistic regression modelling, and predictive performance evaluation to generate actionable insights for churn management.

---

## Research Objectives
- To examine the impact of service quality indicators (call failures and customer complaints) on customer churn  
- To analyse the effect of pricing variables (charge amount and tariff plan) on churn behaviour  
- To assess the influence of customer engagement indicators (frequency of use, SMS usage, subscription length) on churn risk  
- To develop a reliable and interpretable churn prediction model for managerial decision-making  

---

## Dataset Description
- **Dataset Name:** Telco Customer Churn  
- **Source:** UCI Machine Learning Repository  
- **Link:** https://archive.ics.uci.edu/dataset/563/telco+customer+churn  
- **Observations:** 3,150 customers  
- **Data Type:** Secondary, anonymised customer-level data  

### Key Variables
- **Dependent Variable:**  
  - Churn (Binary: 1 = Churned, 0 = Retained)

- **Service Quality Variables:**  
  - Call Failure  
  - Complaints  

- **Pricing Variables:**  
  - Charge Amount  
  - Tariff Plan  

- **Customer Engagement Variables:**  
  - Subscription Length  
  - Frequency of Use  
  - Frequency of SMS  

---

## Methodology
The study adopts a quantitative, cross-sectional research design. Data analysis was conducted using Python programming language with standard data science libraries.

### Analytical Steps
1. Data screening and cleaning  
2. Descriptive statistical analysis  
3. Correlation analysis  
4. Logistic regression modelling  
5. Model performance evaluation using accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC  

All analytical steps were executed using reproducible scripts and notebooks to ensure transparency and academic rigour.

---

## Tools and Technologies
- Python 3  
- pandas  
- NumPy  
- scikit-learn  
- statsmodels  
- matplotlib  
- seaborn  
- Jupyter Notebook  

---

## Key Findings
- Customer complaints are the strongest predictor of churn  
- Call failures significantly increase churn probability  
- Higher customer engagement (usage frequency and SMS activity) reduces churn risk  
- Higher charge amounts are associated with lower churn, indicating the role of perceived value  
- Tariff plan type does not have a significant independent effect on churn  
- The final model achieved:
  - **Accuracy:** 90.3%  
  - **ROC-AUC:** 0.912  

---

## Model Performance Summary
- Strong discrimination between churned and non-churned customers  
- High precision in identifying high-risk churn customers  
- Conservative churn prediction behaviour with lower recall for churn class  
- Suitable for targeted and cost-effective retention strategies  

---

## Ethical Considerations
The dataset used in this research is publicly available and fully anonymised. No personal or identifiable customer information is included. The study complies with ethical standards for secondary data analysis, transparency, and academic integrity.

---

## Reproducibility
All data preprocessing, analysis, and modelling procedures are fully documented and reproducible. The repository supports independent verification of results by supervisors and examiners.

---

## Author
MSc Dissertation Project  
Business Analytics  

---

## License
This repository is intended for academic and research purposes only.
