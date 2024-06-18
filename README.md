# Credit Card Fraud Analysis

## Background

Credit card  fraud is a significant challenge for financial institutions, impacting both operational and customer trust. To address this issue, it is crucial for credit card companies to optimze staffing levels, analyze the susceptibility of different types of credit cards to fraud, and identify geographical regions with higher incidences of flagged accounts.

The project aims to conduct a comprehensive analysis using a customer-level dataset obtained from the <code style ="color:blue">[Kaggle Website](https://www.kaggle.com/code/teamincribo/credit-card-fraud-dataset/input)</code>. This dataset has a total of 8.000 transactions, out of which 3989 have been flagged as suspicious. By leveraging this data, the project will:
1. **Optimize Staffing Levels** : Analyze the frequency of suspected fraudulent activities at different times of day to ensure that staffing is both effective and efficinet.
2. **Brand Analysis** : Determine if specific types of credit cards are more prone to fraudulent activities.
3. **Geolocation Analysis** : Pinpoint geographical regions, including specific countries and cities, that exhibit higher rates of fraud. 

These analyses are essential for developing strategies that reduce operational costs, enhance the allocation of resources, and maintain the trust and confidence of customers in the credit card services. 

## Uderstanding and Defining Flag Account

A flagged account refers to a credit card account that has been marked for further investigation due to suspected fraudulent activities. This designation is typically applied when a transaction or series of transactions exhibit unusual patterns or characteristics that deviate from normal behavior, triggering alerts based on predefined criteria. 

Flagging an account allows financial institutions to temporarily restrict activities, conduct detailed reviews, and take appropriate actions to prevent potential fraud and protect both the customer and the institution.

## Data Dictionary
The metadata can be downloaded using this<code style ="color:blue">[link](https://github.com/incribo-inc/credit_card_fraud/blob/main/credit_card_fraud.csv)</code>.

The data set includes credit card transactions made by credit card holders from .....countries, shows a highly imbalanced dataset with a significant portion of transactions (nearly 50%) flagged for suspected fraudulent activity, indicating a substantial presence of potential fraud cases requiring detailed analysis. 

The column 'Fraud Flag or Label' is a binary column where 1 indicates a transaction flagged for fraud, and 0  indicates a non-fraudulent transaction.