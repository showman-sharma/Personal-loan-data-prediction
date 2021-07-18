# Personal-loan-data-prediction

## Will the person take a bank loan? 
**Objective:** The classification goal is to predict the likelihood of a liability customer buying personal loans.  
## Steps and tasks:  
1. Read the column description and ensure you understand each attribute well 
2. Study the data distribution in each attribute, share your findings 
3. Get the target column distribution. 
4. Split the data into training and test set in the ratio of 70:20 respectively
5. Use different classification models to predict the likelihood of a liability customer buying personal loans 
6. Print the confusion matrix and ROC plots for all the above models


## About file:
Attribute Information:

1. ID : Customer ID

2. Age : Customer's age in completed years

3. Experience : #years of professional experience

4. Income : Annual income of the customer in dollars

5. ZIP Code : Home Address ZIP code.

6. Family : Family size of the customer

7. CCAvg : Avg. spending on credit cards per month in dollars

8. Education : Education Level.
    1. Undergrad;
    2. Graduate;
    3. Advanced/Professional

9. Mortgage : Value of house mortgage if any, in dollars

10. Personal Loan : Did this customer accept the personal loan offered in the last campaign?

11. Securities Account : Does the customer have a securities account with the bank?

12. CD Account : Does the customer have a certificate of deposit (CD) account with the bank?

13. Online : Does the customer use internet banking facilities?

14. Credit card : Does the customer use a credit card issued by

## Conclusion
The following models have given ultimate performace for the given data after scaling and upweighting with test and train scores greater than 99.5%

1. Decision Tree (Unpruned)
2. Decision Tree (Pruned)
3. Bagging
4. Gradient Boosing
5. Adaboosting

It is interesting to note that none of the aforementioned models has mispredicted false negatives.
