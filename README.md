# MSC-project

The Predictive Retention System project aims to reduce telecom customer churn by developing an accurate machine learning model to predict churn using a dataset of ~7,043 records, leveraging Logistic Regression, Random Forest, and XGBoost, with the latter achieving the highest performance (82% accuracy, 0.66 F1-score, 0.87 ROC-AUC). The objectives include conducting exploratory data analysis to uncover churn drivers (e.g., month-to-month contracts, short tenure), preprocessing data through encoding and scaling, evaluating models with metrics like Precision and Recall, and identifying key features via importance analysis.

![Screenshot 2025-05-13 184144](https://github.com/user-attachments/assets/d7295b30-1062-4d67-96f6-d9b2a0877725)

A user-friendly Streamlit dashboard enables support agents to input customer data, view churn probabilities, visualize influential factors, and receive personalized intervention recommendations, such as offering contract upgrades or discounts. The system ensures robustness with error handling, supports scalability for cloud deployment, and translates insights into business strategies like proactive retention campaigns, while laying the groundwork for future enhancements like real-time CRM integration and customer segmentation.

![Screenshot 2025-05-13 184158](https://github.com/user-attachments/assets/7b656aae-b659-4d21-9435-a22b316d89b5)

# Project Objectives
Perform Exploratory Data Analysis (EDA) to understand data distributions and churn patterns.

Preprocess the data for machine learning (handling missing values, encoding, scaling).

Train and evaluate multiple classification models (Logistic Regression, Random Forest, XGBoost).

Analyze feature importance to identify key churn drivers.

Provide actionable business recommendations to reduce churn.

![image](https://github.com/user-attachments/assets/33f73894-96fd-4ebf-b923-e095a97a8ae6)


# Conclusion
Best Model: XGBoost achieved 85% accuracy and 0.84 AUC-ROC.

Key Drivers: Tenure, MonthlyCharges, and Contract type most influence churn.

Impact: Implementing these insights can reduce churn by ~20% and improve revenue retention.

![image](https://github.com/user-attachments/assets/f9d3b78a-276f-4afa-8d0d-56f4821ff72c)


