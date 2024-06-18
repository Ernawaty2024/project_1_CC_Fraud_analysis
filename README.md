# Credit Card Fraud Analysis

## Group 2
Team members : 
- Jimmy Kim
- Thet Win
- Mounika Lingala
- Ernawaty, Ernawaty


## Task
Exploratory Data Analysis and Visualization

## Background

Credit card  fraud is a significant challenge for financial institutions, impacting both operational and customer trust. To address this issue, it is crucial for credit card companies to optimze staffing levels, analyze the susceptibility of different types of credit cards to fraud, and identify geographical regions with higher incidences of flagged accounts.

The project aims to conduct a comprehensive analysis using a customer-level dataset obtained from the <code style ="color:blue">[Kaggle Website](https://www.kaggle.com/code/teamincribo/credit-card-fraud-dataset/input)</code>. This dataset has a total of 8.000 transactions, out of which 3989 have been flagged as suspicious. By leveraging this data, the project will:
1. **Optimize Staffing Levels** : Analyze the frequency of suspected fraudulent activities at different times of day to ensure that staffing is both effective and efficinet.
2. **Brand Analysis** : Determine if specific types of credit cards are more prone to fraudulent activities.
3. **Geolocation Analysis** : Pinpoint geographical regions, including specific countries and cities, that exhibit higher rates of fraud. 

These analyses are essential for developing strategies that reduce operational costs, enhance the allocation of resources, and maintain the trust and confidence of customers in the credit card services. 

## Understanding and Defining Flag Account

A flagged account refers to a credit card account that has been marked for further investigation due to suspected fraudulent activities. This designation is typically applied when a transaction or series of transactions exhibit unusual patterns or characteristics that deviate from normal behavior, triggering alerts based on predefined criteria. 

Flagging an account allows financial institutions to temporarily restrict activities, conduct detailed reviews, and take appropriate actions to prevent potential fraud and protect both the customer and the institution.

This dataset was selected due to its substantial size and high proportion of flagged transactions, which provides a robust foundation for analyzing patterns of fraud. 
The presence of nearly 50% flagged transactions enables a thorough investigation into time-based staffing optimization, brand susceptibility to fraud, and geographical fraud hotspots. This comprehensive analysis is crucial for developing effective fraud prevention strategies and improving operational efficiency in credit card companies.

## Data Dictionary
The data set used in this project is sourced from the credit card fraud repository available on the GitHub platform, maintained by incribo-inc. and can be downloaded using this<code style ="color:blue">[link](https://github.com/incribo-inc/credit_card_fraud/blob/main/credit_card_fraud.csv)</code>.

The column 'Fraud Flag or Label' is a binary column where:
- `1` indicates a transaction flagged for fraud
- `0`  indicates a non-fraudulent transaction

## Project Structure
1. **Data Cleaning**: Preprocesses and clean the dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Explore data distributions, correlations, and patterns.
3. **Visualization**: Create visual representations to better understand the data.
4. **Statistical Analysis**: Perform statistical tests to validate findings.
5. **Conclusion**: Summarize insights and proporse actionable recommendations.

## Conclusion
This project will provide insight into optimizing fraud detection strategies, enhancing operational efficiencies, and safeguarding customer trust. For further details, refer to the notebooks and scripts within this repository.