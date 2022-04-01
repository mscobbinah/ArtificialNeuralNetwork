# Customer Churn Model Using Artificial Neural Network
This is a simple implementation using Artificial Neural Network to identify which customers in a bank are morely likely to leave the bank or not.

## Introduction
Customer retention is one of the primary KPI for financial industries with a subscription-based business model. Competition is tough particularly in the Retail Financial Market where customers are free to choose from plenty of providers. One bad experience and customer may just move to the competitor resulting in customer churn.
Customer churn here is the percentage of customers that stopped using the banking product or service during a certain time frame. One of the ways to calculate a churn rate is to divide the number of customers lost during a given time interval by the number of active customers at the beginning of the period.

## How the ANN model was built and  used 
The primary objective of the customer churn predictive model is to creative a predictive models that shows which leaves the bank. In this simple ANN model we used the rectifier and sigmoid activation function along with binary cross enthropy loss function

## DataSet
1. RowNumber: A numeric value associated with each row in the dataset
2. CustomerID : Unique numeric identifier associated with the customer
3. Surname: Last Name of the customer
4. CreditScore: Credit Score rating of the customer (300-900)
5. Geography: Country of Location of  the customer (France, Spain, Germany)
6. Gender: Sex of the Customer( i.e Male or Female)
7. Age: Age of Customer
8. Tenure: How Long the customer has been with the bank
9. Balance: Current holding balance across accounts
10. NumofProducts: Number of Finacial Products the customer uses with the bank (Chequing, Saving, CreditCard etc)
11. HasCrCard: Has a credit card with the bank 0 - No , 1- Yes
12. isActiveMember: Is the accounts assocviated with customer dormant ir active 0 - Dormant, 1 - Active 
13. EstimatedSalary: Annual Estimated Income of the Customer 
14. Exited: Did the customer leve the bank or not 1 - Exited, 0- Did not Exit
