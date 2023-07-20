# fraud-analysis
Fraud Analysis using Machine Learning

## Problem Statement

![Alt text](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.freepik.com%2Ffree-photos-vectors%2Ffraud&psig=AOvVaw1SN8LszOJpkkIpuoQJlWC1&ust=1689936848384000&source=images&cd=vfe&opi=89978449&ved=0CA4QjRxqFwoTCIDZm8ePnYADFQAAAAAdAAAAABAD)

This case requires trainees to develop a model for predicting fraudulent transactions for a financial company and use insights from the model to develop an actionable plan. The data for the case is available in CSV format, with 6362620 rows and 10 columns. Candidates may use any method they wish to develop their machine learning model. Following standard model development procedures, the model should be estimated on the calibration data and tested on the validation data. This case requires both statistical analysis and creativity/judgment. I recommend spending time on both fine-tuning and interpreting the results of your machine-learning model.


Data Source: The dataset can be found [here](https://drive.google.com/file/d/1-PiRIBsztY9CMyEOvRn-Z0bEboa8-E3z/view?usp=sharing).

### Your task is to execute the process for proactive detection of fraud while answering the following questions.
- 1. Data cleaning includes missing values, outliers and multi-collinearity.
- 2. Describe your fraud detection model in elaboration.
- 3. How did you select variables to be included in the model?
- 4. Demonstrate the performance of the model by using the best set of tools.
- 5. What are the key factors that predict fraudulent customers?
- 6. Do these factors make sense? If yes, How? If not, How not?
- 7. What kind of prevention should be adopted while the company update its infrastructure?
- 8. Assuming these actions have been implemented, how would you determine if they work?


## Features- 

- `step` - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).

- `type` - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

- `amount` - amount of the transaction in local currency.

- `nameOrig` - customer who started the transaction

- `oldbalanceOrg` - initial balance before the transaction

- `newbalanceOrig` - new balance after the transaction

- `nameDest` - customer who is the recipient of the transaction

- `oldbalanceDest` - initial balance recipient before the transaction. Note that there is not information for customers that start with M (Merchants).

- `newbalanceDest` - new balance recipient after the transaction. Note that there is not information for customers that start with M (Merchants).

- `isFraud` - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behavior of the agents aims to profit by taking control or customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

- `isFlaggedFraud` - The business model aims to control massive transfers from one account to another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more than 200.000 in a single transaction.

