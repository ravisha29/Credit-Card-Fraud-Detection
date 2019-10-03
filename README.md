# Credit-Card-Fraud-Detection

Financial fraud is a major issue faced by the public and the government. Credit card fraud is a part of financial fraud. So to overcome this issue data mining techniques have been used to provide support to the stakeholders. In this paper we have presented an overview of fraud detection in credit cards, comparison among various data mining methods such as classification, clustering, regression, forecasting to analyze the data of the stakeholders through which we will identify all the patterns that lead to fraud. High level verification should be added to the banking processes once the fraud patterns are found.


In this project we are presenting a comparison between different techniques to tackle credit card fraud detection which will make online banking secure for people and also help government keep a check on such things. Various data mining techniques can be used to detect fraud, in this project we have made a comparison between decision trees, logistic regression, neural network and clustering. Through these techniques we will find recall, accuracy, precision, F-score and AUC (area under curve). These classifications will help us find the trueness of the data set we have used. We will be using one test data set and two train data set in this solution. 
We often think how accurate a model will be at the time of testing so to get the best results we check various parameters.

We will be using calculating precision to find out how accurate our model is. We will check those marked positive value and check if they are actually positive or not. Precision is a good measure to determine when the false positive rate is very high. So in credit card fraud detection, a false positive means that a transaction which is valid and positive has been marked fraud and false. The user might lose transactions if the precision is not set high for fraud detection. 

"Precision = True Positive ÷ True Positive + False Positive"

Recall value indicates how many true positives our model has through labeling it as positive. So, applying the same thing, recall is the model metric that is used to select the best model when the cost is high along with false negative.  So in a fraud detection system if an actual transaction is predicted as negative then it can be very bad for the bank. 

"Recall = True Positive ÷ True Positive + False negative "
