## Insurance Benefits Obfuscated Model

In this project a predictive model was created to identify which users are likely to utilize insurance benefits. This model involves obfuscating data for privacy and data security.

The data masking (or data obfuscation) should ensure that personal information remains secure even if the data is compromised, while still maintaining the quality of the machine learning models. The goal is to demonstrate that the algorithm works correctly, not necessarily to optimize the model.

Link: ...

### Table of Contents

- Introduction
- Objectives
- Methodology
- Conclusions

### Introduction

The client nicknamed "Sure Tomorrow Insurance Company" aims to leverage Machine Learning to address several tasks, and you are asked to evaluate its feasibility:

- Identify customers similar to a given customer to assist the company's agents with targeted marketing.
- Predict whether a new customer is likely to receive an insurance benefit, comparing the performance of a trained model against an untrained dummy model.
- Use a linear regression model to predict the number of insurance benefits a new customer might receive.
- Implement a data masking algorithm to protect clients' personal information without compromising the model's performance.

### Objectives

- Identify and predict customers receiving insurance benefits.
- Create a data masking algorithm to protect personal data.

### Methodology

- Data Preprocessing & Exploratory Data Anlysis: Data is loaded and ensured free from errors. EDA performed to visualize and derive key statistics from the data.
- Grouping Similar Customers: KNN methodology is used to identify customers with similar characteristics.
- Set up Target: Define target as insurance benefits received and train the predictive model.
- Obfuscate data using invertible matrices. Test the model for changes in accuracy.

### Conclusions

- A predictive model can be built to achieve both identification and obfuscation and optimized for accuracy by scaling the data. 
- In linear regression with obfuscation, the RMSE and R^2 for original and obfuscated data are mathematically the same, provide that obfuscation can be used for ethical model training. Any difference in numerical results is due to rounding errors.
