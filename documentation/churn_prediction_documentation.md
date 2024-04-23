## Churn Prediction for Dummies
A gentle and short guide to solve a real-world business problem with machine learning.

### Introduction

In this repository we will analyze [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) from Kaggle and explore business oportunities to reduce churn customer and for consequence increase retention.

What you'll learn here:
- Problem Framing: Important business aspects of churn prediction
- Data Preparation
- Model Training and Evaluate Results: A step-by-step of how using machine learning to predict churn customers
- MLOps: The path of integrate machine learning with business operations and scale your results

### Problem Framing: Important business aspects of churn prediction

As your business grows and your focus shift from acquiring news customers to retaining existing ones, churn prediction becomes an invaluable tool.

Take a moment to think. Churn is expensive. The cost of any new customer acquisition is always higher than the cost of retaining existing customers. You could look for a Saas companies with subscription business model or non-governmental organizations with recurrent donations, this is an business issue idenpendly of size company or industry.

Accurate churn prediction help you improve the customer experience and prevent voluntary churns. The result is a decline in the churn rate and an increase in retention and LTV of customers.

Therefore, predicting customer churn before it happens is an important part of modern business management.
- Provide more targeted re-engagement campaigns for at-risk customers
- Create more focused customer education content to increase customer lifetime value (LTV).
- On a large scale, churn trends can help marketers build customers personas to target a market segment with better messaging and boost customer acquisition.

### Data Preparation

After we sets important aspects of churn prediction, let's take a look in our data. 

The Telco Customer Churn data contains information about a fictional telco company that provide home phone and internet services to 7043 customers. The data set includes information about:

- Demographic Information About Customers (gender, senior citizen, partner, dependents)
- Customer Account Information (how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges)
- Services that Each Customer has Signed Up For (phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies)
- Churn Target Column: Whether the customer churned or not (Yes or No)

The first step to creating a churn model is to collect relevant data, including product/service usage data, direct feedback data, customer account information, demographic info about customers, and every data you have about your customers. In other words, this step involves gathering relevant data and preparing it for use in your model.

This is very important and we usually spent more time in this step when you don't have a functional pipeline. 

We need to say a big thank you to Kaggle because in our dataset we have all features created including target, but in real-world our data are spread trhough the company, we need to check quality data, apply feature engineering to create relevant features that frame the problem and define the target. This is not easy when you are at the begining of this journey. 

But if you are starting remember the point is:
- Start small with great business definitions that will guide you.
- Data Preparation is a iterate proccess, so you analyze feature by feature, combine somes to create new feature one. Ever trying to represent different aspects of data (demographic, account information, product/service information).
- After some iterations, probability you'll have a bunch of features and then you could try analyze the main metrics for your business and create experiments using machine learning. It's commom found a group of features that fit well and others not, but remember to iterate the process and create more features.


### References
- [How to Build a Churn Prediction Model to Predict Customer Churn](https://userpilot.com/blog/churn-prediction/#:~:text=A%20churn%20model%20works%20by,proactive%20action%20to%20retain%20customers)



