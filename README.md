# Credit_Risk_Analysis

## Overview

Since good loans easily exceed dangerous loans, credit risk is a classification issue that is intrinsically out of balance. As a result, we used several strategies while training and analyzing models with unbalanced classes. We constructed and assess models utilizing resampling using the imbalanced-learn and scikit-learn libraries.

We oversample the data using the RandomOverSampler and SMOTE algorithms and undersample the data using the ClusterCentroids method using the credit card credit dataset from LendingClub, a peer-to-peer lending services provider. The SMOTEENN algorithm is a combinatorial manner of over- and undersampling. In order to estimate credit risk, we contrasted BalancedRandomForestClassifier and EasyEnsembleClassifier, two novel machine learning models that eliminate bias. 

## 
