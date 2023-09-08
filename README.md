# Predicting_Credit_Card_Approvals
Commercial banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. In this notebook, we will build an automatic credit card approval predictor using machine learning techniques, just like the real banks do.

## Solution Steps 
1- Loading and viewing the dataset

       A- Read data

       B- Describe

       C- Get informations about data

       D- Drop unuseful columns



2- Splitting the dataset into train and test sets



3- Handling the missing valuesConvert any signs to NAN using np.NAN

       A- Fill nan in numeric columns by mean

       B- Fill nan in categorical columns by most frequent values



4- Preprocessing the data

       A- Encode non-numeric

       A- Scale the feature values to a uniform range.



5- Fitting a logistic regression model to the train set



6- Making predictions and evaluating performance using

       A- Accuracy

       B- Confusion Matrix



7- Grid searching and making the model perform better

## Conclusion 
Accuracy of logistic regression classifier:  1.0 <br>
 confusion matrix <br>
 [[103   0] <br>
 [  0 125]]
