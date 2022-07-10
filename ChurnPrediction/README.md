# Churn Prediction

### Executive Summary
This project was completed in June 2022 using the IBM Churn Dataset of Telco customers. The project aims at developing a classification model to predict customer churn using the features presented below. Key takeaways:

1. 26.58% of customers have stopped using the product
2. The most common churn reasons are attitude of support person (10.2%), competitor offered higher download speeds (10.1%) and competitor offered more data (8.6%)
3. 5 classification models were developed to examine the best algorithm and configuration to address the problem, including Logistic Regression, Decision Tree, Random Forest, Ada Boosting, and Gradient Boosting
4. Logistic Regression appears to be the best performing model with the highest accuracy rate (78.11%), the highest AUC (0.86), and the lowest computational time (13.39 seconds).

### Data Dictionary
| Field  | Description |
| ------------- | ------------- |
| CustomerID | A unique ID that identifies each customer |
| Count | A value used in reporting/dashboarding to sum up the number of customers in a filtered set |
| Country | The country of the customer’s primary residence |
| State | The state of the customer’s primary residence |
| City | The city of the customer’s primary residence |
| ZIP code | The zip code of the customer’s primary residence |
| Lat Long | The combined latitude and longitude of the customer’s primary residence |
| Latitude | The latitude of the customer’s primary residence |
| Longitude | The longitude of the customer’s primary residence |
| Gender | The customer’s gender: Male, Female |
| Senior Citizen | Indicates if the customer is 65 or older: Yes, No |
| Partner | Indicate if the customer has a partner: Yes, No |
| Dependents |  Indicates if the customer lives with any dependents: Yes, No. Dependents could be children, parents, grandparents, etc. |
| Tenure Months | Indicates the total amount of months that the customer has been with the company by the end of the quarter specified above |
| Phone Service | Indicates if the customer subscribes to home phone service with the company: Yes, No |
| Multiple Lines | Indicates if the customer subscribes to multiple telephone lines with the company: Yes, No |
| Internet Service | Indicates if the customer subscribes to Internet service with the company: No, DSL, Fiber Optic, Cable |
| Online Security | Indicates if the customer subscribes to an additional online security service provided by the company: Yes, No |
| Online Backup | Indicates if the customer subscribes to an additional online backup service provided by the company: Yes, No |
| Device Protection |  Indicates if the customer subscribes to an additional device protection plan for their Internet equipment provided by the company: Yes, No |
| Tech Support | Indicates if the customer subscribes to an additional technical support plan from the company with reduced wait times: Yes, No |
| Streaming TV | Indicates if the customer uses their Internet service to stream television programing from a third party provider: Yes, No. The company does not charge an additional fee for this service |
| Streaming Movies | Indicates if the customer uses their Internet service to stream movies from a third party provider: Yes, No. The company does not charge an additional fee for this service |
| Contract | Indicates the customer’s current contract type: Month-to-Month, One Year, Two Year |
| Papaerless Billing | Indicates if the customer has chosen paperless billing: Yes, No |
| Payment Method | Indicates how the customer pays their bill: Bank Withdrawal, Credit Card, Mailed Check |
| Monthly Charge | Indicates the customer’s current total monthly charge for all their services from the company |
| Total Charges | Indicates the customer’s total charges, calculated to the end of the quarter specified above |
| Churn Label | Yes = the customer left the company this quarter. No = the customer remained with the company. Directly related to Churn Value |
| Churn Reason | A customer’s specific reason for leaving the company. Directly related to Churn Category |



##### Author: © Hutami Nadya Larasati 2022
