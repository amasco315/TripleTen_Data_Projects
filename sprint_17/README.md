# Final Project

The telecom operator Interconnect would like to be able to forecast their churn of clients. If it's discovered that a user is planning to leave, they will be offered promotional codes and special plan options. Interconnect's marketing team has collected some of their clientele's personal data, including information about their plans and contracts. /
Interconnect's services
Interconnect mainly provides two types of services:

Landline communication. The telephone can be connected to several lines simultaneously.
Internet. The network can be set up via a telephone line (DSL, digital subscriber line) or through a fiber optic cable.
Some other services the company provides include:

Internet security: antivirus software (DeviceProtection) and a malicious website blocker (OnlineSecurity)
A dedicated technical support line (TechSupport)
Cloud file storage and data backup (OnlineBackup)
TV streaming (StreamingTV) and a movie directory (StreamingMovies)
The clients can choose either a monthly payment or sign a 1- or 2-year contract. They can use various payment methods and receive an electronic invoice after a transaction.

## The Data
The data consists of files obtained from different sources:

- contract.csv — contract information
- personal.csv — the client's personal data
- internet.csv — information about Internet services
- phone.csv — information about telephone services
In each file, the column customerID contains a unique code assigned to each client.

The contract information is valid as of February 1, 2020.

## The Process 
All datasets were loaded and preprocessed. I then merged the datasets on the customer_id column in order to make one complete dataset with all the relevant customer information. After the datasets were merged, I took care of any missing values that arose. I then conducted EDA, using data visualization and the groupby method to check for trends among the customers who had already churned. After this, feature engineering was performed to ensure that all categorical features were made numerical. I then went on to build and tune 3 different types of models in order to see which was best suited for determining the churn of Interconnects's clients.

## The Results 
For detailed results from this project please see the conclusion section of the notebook. 