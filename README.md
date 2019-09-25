# Credit_CardML (Built by Shashi and Toshendra)
This Credit_CardML consist of datasets that contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. It contains only numerical input variables which are the result of a PCA transformation. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

The Presented Code solves this anomaly problem using Naives Bayes, SVM and Isolation Forest(Best). While Naives Bayes and SVM are self implemented, Isolation Forest is learnt from forums and then implemented.

Dataset is acquired by http://mlg.ulb.ac.be/ 
Link to Dataset https://drive.google.com/open?id=100TnhGcnDLAK-k0xAKfaPPkeOV6jtHrj
