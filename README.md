# Telco Customer Churn Prediction  

This project predicts whether a customer will churn (leave the company) using machine learning techniques.  

## Dataset  
- Dataset: [Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)  
- Rows: 7043 | Columns: 21  
- Target Column: `Churn`
- 
## Key Features
1. Data Cleaning & Transformation

 Handled missing and inconsistent values (e.g., TotalCharges column).
 Converted categorical variables using encoding techniques.

2. Exploratory Data Analysis (EDA)

 Identified patterns like churn rates by contract type, payment method, internet service, etc.
 Compared senior citizen vs non-senior churn rates.

3. Machine Learning Models

 Logistic Regression
 Random Forest Classifier
 Support Vector Machine (SVM)

4. Model Evaluation
 Accuracy, Precision, Recall, F1-score, and Confusion Matrix analysis.

## Visualizations
Here are some examples from the analysis:
Churn rate by Contract Type
Churn rate by Payment Method
Internet Service vs Churn

Support Vector Machine (SVM)
## Steps in the Project  
1. Data Cleaning & Handling Missing Values  
2. Exploratory Data Analysis (EDA) – understanding patterns in churn  
3. Feature Encoding & Transformation  
4. Model Building (Logistic Regression, Random Forest, etc.)  
5. Model Evaluation & Results  

## Key Insights  
- Month-to-month contracts have the highest churn rate.  
- Electronic check payment method is most common among churners.  
- Customers with fiber optic internet service churn more frequently.  

## Tools & Libraries  
`Python`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  

## Results  
- Achieved **81.4% accuracy** using Random Forest Classifier.  
- Logistic Regression achieved **79.2% accuracy**.  

