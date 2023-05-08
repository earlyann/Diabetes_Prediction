## Health Clusters and Diabetes Prediction
### Project Overview
In this project, we used the KMeans clustering algorithm to identify clusters within a dataset of individuals' health data. We then built predictive models using logistic regression, support vector machines (SVM), and XGBoost to predict the presence of diabetes in these individuals. To address class imbalance, we applied the Synthetic Minority Over-sampling Technique (SMOTE). We also performed hyperparameter tuning for the XGBoost model.

#### Technologies Used
- Python
- KMeans Clustering
- Logistic Regression
- Support Vector Machines (SVM)
- XGBoost
- Synthetic Minority Over-sampling Technique (SMOTE)
Project Description
We identified three clusters within the health dataset:

Cluster 0: Middle-aged individuals with a higher percentage of females and moderate prevalence of hypertension, heart disease, and diabetes.
Cluster 1: A younger population with relatively low prevalence of health conditions.
Cluster 2: An older population with the highest prevalence of hypertension, heart disease, and diabetes among the clusters.
We built predictive models using logistic regression, SVM, and XGBoost:

The logistic regression model achieved an accuracy of 95.91% on the test dataset. After applying SMOTE, the accuracy decreased to 89.94%, but recall for the positive class (diabetic patients) increased from 0.62 to 0.85.

The SVM model achieved an accuracy of 95.66%. After applying SMOTE, the accuracy decreased to 88.53%, but recall for the positive class (diabetic patients) increased from 0.52 to 0.89.

The XGBoost model with SMOTE achieved an accuracy of 97.08%, with a precision of 0.95, recall of 0.69, and F1-score of 0.80 for the positive class (diabetic patients).

We also performed hyperparameter tuning for the XGBoost model, but it did not result in a significant improvement in performance.

Conclusion
The XGBoost model with SMOTE outperformed the logistic regression and SVM models in terms of accuracy and F1-score for the positive class. Therefore, we recommend using the XGBoost model with SMOTE for predicting diabetes in this dataset. The hyperparameter tuning did not significantly improve the model's performance.




