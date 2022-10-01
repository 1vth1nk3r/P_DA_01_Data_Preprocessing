# P_DA_01_preprocessing
The project from the Data Preprocessing sprint of the Practicum DA/DS course.

## Description

Here we have a small dataset on bank clients' past loans. We would like to build a **credit scoring** of a potential customer. Our goal is to find out if a customer’s marital status and number of children has an impact on whether they will default on a loan. The bank already has some data on customers’ credit worthiness.

First, we should do some data preprocessing: fill in the missing values, correct the faulty ones, clean spelling errors, and change data types. Also, splitting customers into categories by income would be helpful for this task. After doing so, we could explore our data and. 

## Conclusion
  * We don't see that customers' marital status influences whether they will repay. Instead, we could make predictions based on a person's age (The older is the customer, the safer is the loan).
  * Also, having any number of children negatively affects the chance of default.
  * There is no correlation between income and the chance of repaying.
  * We could make predictions based on the purpose of the loan. For example, all purposes related to real estate are safe while getting an education or buying a car are the riskiest.
