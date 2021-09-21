## A/B Analysis - email Campaign

### About this project

This project is an A/B Test, I will analyze the results of an email campaign experiment, which main objective is to influence customers to make a decision. I will apply the test of means analysis to verify weather the results of the campaign are occurring by chance or because the email strategy is working as expected.

### The Experiment

- Number of participants: 100,000
- Percentage of customers who received the email: 50.01%
- Percentage of customers who did not receive the email: 49.98%
- 3 markets:  San Francisco, Los Angeles and Sacramento
- Date Range:  Mar/1/2021 – Mar/31/2021


### Dataset

The data set contains one row for each customer that participated in the month of the experiment (March, 2021), with the following columns:

1. id - customer ID
2. group - the group the customer was assigned 
- 0 = control group (did not receive an email) 
- 1 = test group (received an email)
3. make_decision - indicator for the customer make a decision 
- 0 = no, the customer did not make a decision
- 1 = yes, the customer did make a decision
4. market - region for which the customers has received an email
6. score - the customer’s credit score, ranging from 0 (low risk) to 1 (high risk)
7. date - the date on which the email was sent

### Tech and Topics:

- A/B Test
- Test of means
- Python 3
- scipy.stats as stats
- matplotlib
- seaborn

### Author
[Wendy Navarrete](http://wendynavarrete.com)
