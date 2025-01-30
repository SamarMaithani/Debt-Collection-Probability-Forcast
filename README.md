# Debt-Collection-Probability-Forcast

# About the Project
This project endeavors to develop a sophisticated machine-learning model aimed at accurately predicting the probability of successfully collecting debts by meticulously examining the statute-barred status of each account.

The Given dataset provides a multitude of attributes including original creditor information, account IDs, current balances, purchase dates, and a wealth of other pertinent features. The focal point of this endeavor centers on the IsStatBarred field ‘Y’ status, which serves as the pivotal target variable for classification. 

To make any sort of prediction from the data, the data is first cleaned, all the duplicates and missing values and all are delt with, then some EDA is performed on the data to remove any outliers and to discover any correlation between the features and after applying some pre-processing techniques a classification ML model is used to figure out the Barred Status of the Account.

# About the Data
The data Presented to us consists of 400000+ observations and 21 features + 1 target attribute. Attributes given in dataset as:

- EntityID: Unique identifier for each entry.
- OriginalCreditor[Redacted]: Name of the original creditor, with sensitive information redacted.
- AccountID: Unique identifier for the account.
- Current Balance: The current balance of the account.
- DebtLoadPrincipal: The principal amount of the debt load.
- BalanceAtDebtLoad: The balance at the time of debt load.
- PurchasePrice: The price at which the debt was purchased.
- ProductOrDebtType: Type of product or debt.
- CollectionStatus: Status of the debt collection 
- CloseDate: The date when the account was closed.
- Closure Reason: Reason for closing the account.
- InBankruptcy: Indicates if the account is involved in bankruptcy.
- AccountInsolvencyType: Type of insolvency related to the account.
- CustomerInsolvencyType: Type of insolvency related to the customer.
- IsLegal: Indicates if legal action has been taken.
- Interest Rate: Interest rate associated with the debt.
- LastPaymentAmount: Amount of the last payment made.
- LastPaymentMethod: Method used for the last payment.
- NumLiableParties: Number of liable parties associated with the account.
- CustomerAge: Age of the customer.
- NumPhones: Number of phone contacts associated with the customer.
- NumEmails: Number of email contacts associated with the customer.
- NumAddresses: Number of addresses associated with the customer.
- IsStatBarred: Indicates if the debt is statute-barred.

# Classification Models Result
![image](https://github.com/user-attachments/assets/a1e2a9ba-dc36-4a1f-8454-3e93092a31fc)

# Confusion Matrix
![image](https://github.com/user-attachments/assets/b3d11666-3c9e-4dc2-84b4-469564f1fa74)



# Conclusion
In the realm of debt collection, the ability to discern which accounts are statute-barred—thus potentially unrecoverable—holds immense significance.  ThIS project has demonstrated the application of Machine Learning in identifying whether the accounts where the statute barred status and how much remarkable potential it has in enhancing the accuracy of the prediction. And through the confusion matrix we saw that the train and test data is balanced. 

Through the utilization of ensemble techniques and vast dataset we have seen the development of a great model that provides an accuracy of 97%! As the technology's advances, we can expect a greater stride in the accuracy and efficiency of the machine learning models which in turn will contribute to even  debt collection. 





