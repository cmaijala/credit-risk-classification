# Module 12 Report Analysis

Overview of the Analysis
In this analysis, we aimed to build machine learning models to predict the risk of loan defaults. The primary goal was to help lenders make informed decisions by identifying high-risk loans. This would allow financial institutions to mitigate risk by potentially adjusting interest rates, loan terms, or rejection rates based on the model’s predictions.

The data included various financial information about loan applications, such as income, debt-to-income ratio, and loan amount. The main variable we aimed to predict was loan_status, where a value of 0 indicated a healthy (low-risk) loan, and a value of 1 indicated a high-risk loan. By using this target variable, we aimed to create models that would distinguish between high-risk and healthy loans accurately.

Machine Learning Process
Data Preparation: The dataset was cleaned and preprocessed, including separating it into features (X) and labels (y).
Model Selection: We trained and evaluated several machine learning algorithms, including LogisticRegression, on this dataset.
Model Evaluation: Each model was assessed using metrics such as accuracy, precision, and recall, especially for high-risk loans, as these have the most significant implications for lenders.
Results
Machine Learning Model 1 (Logistic Regression):
Accuracy: 0.99 — This high accuracy indicates that the model is very effective at classifying loans overall.
Precision for High-Risk Loans: 0.84 — Among all loans predicted to be high-risk, 84% were actual high-risk loans.
Recall for High-Risk Loans: 0.94 — Out of all high-risk loans, the model correctly identified 94%.
Summary
The logistic regression model performed exceptionally well, with an accuracy of 99% and strong precision and recall scores for high-risk loans. This model effectively identifies high-risk loans while maintaining low false-positive rates for healthy loans.

Recommendation:
Based on the analysis, the logistic regression model is recommended due to its high accuracy and balanced precision and recall. Given that identifying high-risk loans is critical in reducing potential financial losses, the high recall score (0.94) ensures most high-risk loans are correctly classified.
