# Churn Prediction in Banking
This project focuses on developing a classification model to predict customer churn in a bank. Churn refers to the phenomenon where customers discontinue their relationship with a company or institution, in this case, a bank. By accurately identifying potential churners, the bank can take proactive measures to retain valuable customers and mitigate business losses.

## Data Preprocessing
The dataset underwent preprocessing steps to ensure its suitability for training machine learning models. This involved handling missing values, encoding categorical variables(One-Hot Encoding), scaling numerical features, and splitting the data into training and test sets. 

## Classification Algorithms
Three classification algorithms were employed in this project:

1. K-Nearest Neighbors (KNN): This algorithm assigns a class to a new data point based on the classes of its nearest neighbors. By considering the proximity of similar instances, KNN can classify whether a customer is likely to churn or not.

2. Decision Tree: A decision tree is a flowchart-like structure where each internal node represents a feature, each branch represents a decision rule, and each leaf node represents the outcome. 

3. Logistic Regression: It estimates the probability of customer churn based on the relationship between the dependent variables and the target variable.

## Results
GridSearch was performed to explore different combinations of hyperparameters and variables. This approach helped fine-tune the model and identify the best configuration for predicting churn accurately.

After training and evaluating the models on the bank churn dataset, the results indicate that Logistic Regression outperformed the other two in predicting customer churn.

## Conclusion
Logistic Regression model can be used to identify customers at risk of churning and implement targeted retention strategies. By proactively addressing churn, the bank can minimize customer attrition and maximize customer satisfaction, ultimately contributing to business growth and profitability.

