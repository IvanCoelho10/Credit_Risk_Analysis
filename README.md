# Credit_Risk_Analysis

## Overview of the analysis: 

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. 

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results: 

### Balanced Random Forest Classifier

![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/87731897/147423154-62044aee-730c-43c6-af7e-cabe472ef403.png)

### Naive Random Oversampling

![Naive Random Oversampling](https://user-images.githubusercontent.com/87731897/147423160-a8460b69-49a1-461c-b72b-7b1c3aafa2b1.png)

### SMOTE Oversampling

![SMOTE Oversampling](https://user-images.githubusercontent.com/87731897/147423163-e288b6e2-a386-4d5a-8d6b-9edfa1895039.png)

### Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/87731897/147423168-809a6f88-2010-4a91-a580-b7ee1459ad3c.png)

### Combination (Over and Under Sampling)

![Combination (Over and Under) Sampling](https://user-images.githubusercontent.com/87731897/147423171-1774d93e-7188-4e25-bbdf-48803c41091b.png)

### UnderSampling

![Undersampling](https://user-images.githubusercontent.com/87731897/147423174-5c951d56-1747-4c99-96fe-6a086741f40a.png)
