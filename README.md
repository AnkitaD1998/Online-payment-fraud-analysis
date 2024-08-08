# Online-payment-fraud-analysis

![image alt](https://github.com/AnkitaD1998/Online-payment-fraud-analysis/blob/397d0812876810978d37cbc40a01cadfad6e62de/35-min.png)

# Problem Statement
We are living in a digital world where people started approaching current technologies. They make our work easy and it's reliable.

Online payment is one of the scenarios that people started using in recent years. Just one click! One tap! makes our work easier and faster. As much as we know about the merits of online payment, some fraudsters try to loot money from people with different techniques.

With the increase in online payment nowadays, online payment fraud has also been rising and it's a major concern among the people who are not aware of the current technologies.

Let's analyze the online payment fraud detection dataset taken from Kaggle and provide insights on this!!

To identify online payment fraud with data analysis, we need to train for classifying fraudulent and non-fraudulent payments. For this, we need a dataset containing information about online payment fraud to understand what type of transactions lead to fraud. For this task, I collected a dataset from Kaggle, which includes historical information about fraudulent transactions that can be used to detect fraud in online payments.

## Data Description
Engaged in a project that contained historical information on over 63 lakh fraudulent transactions. These columns provide below information:
- step: represents a unit of time where 1 step equals 1 hour
- type: type of online transaction
- amount: the amount of the transaction
- nameOrig: customer starting the transaction
- oldbalanceOrg: balance before the transaction
- newbalanceOrig: balance after the transaction
- nameDest: recipient of the transaction
- oldbalanceDest: initial balance of recipient before the transaction
- newbalanceDest: the new balance of recipient after the transaction
- isFraud: fraud transaction

## Data Pipeline
- Executed data cleaning procedures to prepare the dataset for analysis like outlier handling techniques to enhance data quality and model performance, reducing data anomalies by 95%
- Performed exploratory data analysis (EDA) to gain insights into the characteristics of fraudulent transactions, identifying key fraud patterns
- Recommended actions for future developments, strategic opportunities, and policy enhancements

# Conclusion from EDA
- We have a large number of records that are incorrectly flagged as 0. Incorrect flagging might have a big impact in the future if we don't calculate it properly as it might lead to an increase in online payment fraud percentage as people rely more on online payment nowadays
- The amount range usually fraudsters target is around 1.3-5 lakhs which is certainly a large amount
- Fraudsters focus on cashout and payment mode type transfer
- In total, there is 8213 fraud transactions happened which constitutes around 0.13% of total transactions that happened
- 0.183 % fraud happened in the total cashout mode type and 0.769 % fraud happened in the total transfer mode type
- There is a high correlation between newbalanceOrig, oldbalanceOrg and also between newbalanceDest and oldbalanceDest

# Recommendations
- Implement stricter monitoring and additional verification steps for transactions in the range of 1.3-5 lakhs, as this range is frequently targeted by fraudsters
- Use risk-based authentication methods where higher-risk transactions require additional verification steps, such as multi-factor authentication or biometric verification
- Cashout and Transfer Modes have higher fraud percentages, implement stricter checks and controls specifically for these types of transactions
- Set lower transaction limits for cashout and transfer modes unless the user completes additional verification steps
- Conduct regular awareness campaigns to educate customers about common fraud tactics and how to recognize and report suspicious activities
- Implement real-time transaction alerts via SMS or email to inform customers immediately of any transactions, allowing them to quickly report unauthorized activities














