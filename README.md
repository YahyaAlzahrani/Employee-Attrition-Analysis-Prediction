# Employee Attrition Analysis and Prediction
This project analyzes a dataset of company employees to understand the key factors that lead to attrition (employees leaving the company). Based on this analysis, a machine learning model is built to predict the likelihood of an employee's departure.

Project Goal
The main objective is to help the Human Resources (HR) department understand the drivers of employee turnover and to build a predictive tool that can identify employees who are at high risk of leaving. This allows the company to take proactive steps to retain valuable talent.

Dataset
The dataset used for this project is the "HR Analytics Dataset" sourced from Kaggle. It contains various employee attributes, including:
`satisfaction_level`
`last_evaluation`
`number_project`
`average_montly_hours`
`time_spend_company`
And other work-related features.

Methodology
The project was executed in the following stages:
1.Exploratory Data Analysis (EDA): The data was analyzed to discover trends, patterns, and correlations. A correlation matrix and various visualizations were used to understand the relationships between different features and employee attrition.
2.Data Preprocessing: The dataset was cleaned and prepared for modeling. This included encoding categorical variables to be machine-readable.
3.Model Building: A Multi-layer Perceptron Classifier (MLPClassifier), which is a type of neural network, was trained on the prepared data to classify employees into two categories: "will leave" or "will stay".
4.Model Evaluation: The model's performance was measured using a confusion matrix and key classification metrics.

Results and Key Findings
Key Factors for Attrition: The analysis revealed that the most significant factor correlated with an employee leaving is a low `satisfaction_level`. Other influential factors include the `time_spend_company` and the `number_project` assigned to the employee.
Model Performance: The trained MLPClassifier model achieved strong results in predicting employee attrition:
Accuracy: ~96.1%
Precision: ~94.2%
Recall: ~89.5%
F1 Score: ~91.8%
This high level of accuracy indicates that the model can be a reliable tool for identifying at-risk employees.

Technologies Used
* Python
* Pandas
* NumPy
* Scikit-learn (for MLPClassifier and metrics)
* Matplotlib / Seaborn
* Google Colab
