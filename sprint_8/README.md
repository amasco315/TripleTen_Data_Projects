# Sprint 8 Supervised Learning project
Beta Bank customers are leaving: little by little, chipping away every month. The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones.

We need to predict whether a customer will leave the bank soon. You have the data on clients’ past behavior and termination of contracts with the bank.

Build a model with the maximum possible F1 score. To pass the project, you need an F1 score of at least 0.59. Check the F1 for the test set.

Additionally, measure the AUC-ROC metric and compare it with the F1.

## The Data
The data is taken from one dataset, 
**churn.csv:**
- RowNumber — data string index
- CustomerId — unique customer identifier
- Surname — surname
- CreditScore — credit score
- Geography — country of residence
- Gender — gender
- Age — age
- Tenure — period of maturation for a customer’s fixed deposit (years)
- Balance — account balance
- NumOfProducts — number of banking products used by the customer
- HasCrCard — customer has a credit card
- IsActiveMember — customer’s activeness
- EstimatedSalary — estimated salary
- Exited — сustomer has left

## The Process
First, the dataframe was loaded, and all preprocessing was completed. I then checked to see if there was a class imbalance among the features and the target. Next, I separated the data into Training, Validation, and Test sets. Then, the numerical features were standardized. I went on to build and tune 3 different models, while also using upsampling and downsampling. 

## The Results
The final model chosen was a DecisionTreeClassifier model with an f1_score of 0.59. For more detailed conclusion see the conclusion section of the notebook. 