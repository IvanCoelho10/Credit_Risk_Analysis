# Credit_Risk_Analysis

## Overview of the analysis: 

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. 

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results: 

### Balanced Random Forest Classifier

![2021-12-26 (1)](https://user-images.githubusercontent.com/87731897/147422538-2ed0d672-3ace-4fdd-bbcc-2327f3e96657.png)

### Naive Random Oversampling

![2021-12-26 (2)](https://user-images.githubusercontent.com/87731897/147422539-1110b558-c7a9-4515-ba5f-8e9b689a8e67.png)

### Naive Random Oversampling

![2021-12-26 (3)](https://user-images.githubusercontent.com/87731897/147422541-3340ff8e-f6db-46b4-bc82-53391283cae7.png)

### SMOTE Oversampling

![2021-12-26 (4)](https://user-images.githubusercontent.com/87731897/147422543-e199724d-ed4b-4080-9595-a4b4919f41ee.png)

### Easy Ensemble AdaBoost Classifier

![2021-12-26](https://user-images.githubusercontent.com/87731897/147422546-0941043a-482b-42fc-bf9d-dfd247a00597.png)


