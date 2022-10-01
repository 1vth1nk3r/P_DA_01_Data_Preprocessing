# Analyzing borrowers’ risk of defaulting
The project from the Data Preprocessing sprint of the Practicum DA/DS course.

## Description

Here we have a small dataset on bank clients' past loans. We would like to build a **credit scoring** for a potential customer. Our goal is to determine if a customer's marital status and the number of children impact whether they will default on a loan. The bank already has some data on customers' creditworthiness.

First, we should do some data preprocessing: fill in the missing values, correct the faulty ones, clean spelling errors, and change data types. Also, splitting customers into categories by income would be helpful for this task. After doing so, we could explore our data. 

## Conclusion
  * We don't see that customers' marital status influences whether they will repay. Instead, we could make predictions based on a person's age (The older the customer, the safer the loan).
  * Also, having any number of children negatively affects the chance of default.
  * There is no correlation between income and the chance of repaying.
  * We could make predictions based on the purpose of the loan. For example, all purposes related to real estate are safe, while getting an education or buying a car are the riskiest.
