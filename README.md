# Credit_Risk_Analysis

## Overview

Since good loans easily exceed dangerous loans, credit risk is a classification issue that is intrinsically out of balance. As a result, we used several strategies while training and analyzing models with unbalanced classes. We constructed and assess models utilizing resampling using the imbalanced-learn and scikit-learn libraries.

We oversample the data using the RandomOverSampler and SMOTE algorithms and undersample the data using the ClusterCentroids method using the credit card credit dataset from LendingClub, a peer-to-peer lending services provider. The SMOTEENN algorithm is a combinatorial manner of over- and undersampling. In order to estimate credit risk, we contrasted BalancedRandomForestClassifier and EasyEnsembleClassifier, two novel machine learning models that eliminate bias. 

## Results

<img width="482" alt="balanced accuracy score" src="https://user-images.githubusercontent.com/108194577/197934770-de24cf77-1866-4d06-ae41-900ff59a5de5.PNG">

<img width="513" alt="confusion matric resampling" src="https://user-images.githubusercontent.com/108194577/197934780-a5b4a98e-39c7-418d-9c12-7ac9c283dd69.PNG">


