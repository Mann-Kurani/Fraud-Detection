# Fraud Detection in Payment Gateway

## Problem Description

IndAvenue, a disruptive payment gateway start-up, faces challenges in fraud detection due to its low processing fees strategy. The lack of a robust fraud detection system has resulted in economic burdens for vendors, leading to client attrition. This hackathon involves creating an AI-based model to detect and prevent fraudulent transactions, utilizing a dataset with an `is_fraud` column indicating transaction fraudulence.

## Table of Contents
1. **Problem Description**
2. **Dataset Description**
3. **Hackathon Tasks**
    - Exploratory Analysis
    - ML Modelling
    - Recommendations and Implementation Strategies
4. **Evaluation Metric**

## Dataset Description

Target Attribute: "is_fraud" (binary classes)

**CSV Files:**
- **train_data.csv:** Transaction data with unique transaction numbers, associated labels, and features.
- **test_data.csv:** Test data with features (excluding the target column).
- **Solution.csv:** Model output for test data evaluation.

*Note: Negative values in 'money_transacted' denote amount credited, while positive values signify amount debited.*

## Hackathon Tasks

### Exploratory Analysis

Explore data through visualizations and numerical analysis. Provide insights and patterns observed, explaining the impact of key attributes on the target.

### ML Modelling

Develop a fraud detection framework by enhancing the baseline ML model. Engineer features, fine-tune, and improve model performance.

### Recommendations and Implementation Strategies

Offer business recommendations to IndAvenue. Utilize visualizations to convey recommendations. Explain the ML model in non-technical terms, suggesting strategies for fast customer checkout.

## Evaluation Metric

The F1 Score is the evaluation metric for this hackathon.

---

### Disclaimer:
 The dataset provided for this end-term exam in Methods and Algorithms in Machine Learning -1 is furnished by the university for academic purposes. 
 Please be aware that, given its academic nature, the dataset might contain simulated or artificially introduced data for educational and assessment objectives. 
 It is advised to consider the possibility of inconsistencies or deviations from real-world scenarios in the dataset. 
 The purpose is to evaluate your skills in addressing machine learning challenges rather than reflecting an exact representation of an external, real-world dataset.




