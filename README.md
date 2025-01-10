# CREDIT GUARD : THE LOAN DEFAULT FORESIGHTING
## INTRODUCTION
This document serves as a comprehensive guide for the credit default prediction model developed using Machine Learning (ML) techniques and visualized through Power BI. The model aims to predict the likelihood of loan defaults based on various borrower attributes and loan characteristics, providing valuable insights for financial institutions. Credit default prediction is a critical task in the financial industry. ccurate prediction of credit defaults enables financial institutions to minimize losses, optimize lending decisions, and improve overall portfolio risk management.

## OBJECTIVE
The primary objective of this project is to develop a robust predictive model that can accurately assess the risk of loan defaults. This is achieved by utilizing ML algorithms, specifically Logistic Regression and Random Forest, to analyze historical data. The results are then visualized in Power BI to facilitate decision-making processes for stakeholders. 

## IMPLEMENTATION
### Data Collection
Loading the Dataset: The dataset was collected from the Kaggle Website.
Reading the Dataset: The dataset was read into a Pandas DataFrame for further analysis and manipulation.

Dataset Link - https://www.kaggle.com/datasets/laotse/credit-risk-dataset/data
### Data CLeaning and Manipulation
Dropping Data: Unnecessary or irrelevant rows are removed based on specific criteria.

Handling Missing Values: Missing values in numerical columns are filled with their respective mean values.

Categorical to Numerical Encoding:Categorical variables are transformed into numerical format using encoding techniques like one-hot encoding.

Feature Engineering: Relevant features are selected and concatenated with the dataset for further analysis.

### Data Splitting
The dataset was split into training and testing sets using a 80:20 ratio. The training set was used to train the machine learning models, while the testing set was used to evaluate their performance on unseen data. 

### Data Scaling
Data scaling is performed to normalize feature values, ensuring that the model trains effectively without bias towards any specific feature due to its scale.  The model trains effectively and prevents features with larger scales from dominating the learning process.

### Model Building
Logistic Regression :

A Logistic Regression model was trained on the training data. The models are trained on the scaled training data. The trained model was used to predict the probability of default for the test data. Accuracy, precision, recall and F1 score are calculated using the test data to assess model performance.

Random Forest :

A Random Forest model was trained on the training data. The models are trained on the scaled training data. The trained model was used to predict the probability of default for the test data. Accuracy, precision, recall and F1 score are calculated using the test data to assess model performance.

### Feature Importance
Feature importance was analyzed to identify the most influential factors contributing to credit default predictions. A new feature is created containing true indices alongside predicted values for analysis.

### Saving Dataset into Excel File
The final datasets with predicted probabilities, actual labels, and features was saved as an Excel file.

## POWER BI VISUALIZATION
The saved Excel file is imported into Power BI to create a visual dashboard that includes:

Accuracy Metrics: Displaying model accuracy scores.

Loan Status Scores: Visual representation of predicted loan statuses.

Charts: Various charts illustrating key insights derived from the model predictions.

[MODEL 1 DASHBOARD](https://github.com/Ujjwal-Jaiswal-UJ/credit-guard-loan-default-prediction/blob/fa7b8c3060ea206b478b82e6e88d1d03a5a1c9de/Model1.png)

This comprehensive approach ensures that stakeholders can visualize and interpret the credit risk assessment effectively, aiding in informed decision-making regarding loan approvals and risk management strategies.

## CONCLUSION
The project successfully demonstrated the development and evaluation of machine learning models for credit default prediction. By combining Python for model training and Power BI for visualization and analysis, I gained valuable insights into the factors driving credit risk. The findings from this project can inform lending decisions, optimize risk assessment processes, and ultimately enhance the profitability and stability of financial institutions.

[Credit Guard - The Credit Default Foresighting Presentation](https://www.canva.com/design/DAGbr72e820/ofwsPstNGvsS9dnIBKYenA/view?utm_content=DAGbr72e820&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h6a53200148)<br>
[CREDIT GUARD - Power BI File](https://1drv.ms/u/c/206bbe20bed39524/EV3W4kgGC3ZItaHpjBFHyFsBAR9YVcZ2TQfG9_0U_GudjA?e=AWBASS)





