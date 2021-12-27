# Credit_Risk_Analysis

## Overview of the analysis: 

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. 

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results: 

### Balanced Random Forest Classifier

![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/87731897/147422954-7f066212-c8a4-4480-8823-2750a8461036.png)

### Naive Random Oversampling

![Naive Random Oversampling](https://user-images.githubusercontent.com/87731897/147422957-e3a81f25-f8d3-42de-a608-30e850f91787.png)

### SMOTE Oversampling

![SMOTE Oversampling](https://user-images.githubusercontent.com/87731897/147422970-74f45535-831c-445d-a36d-20a27d92f997.png)

### Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/87731897/147422975-6fc346a2-15f6-409e-9ab9-466009d088d5.png)

### Combination (Over and Under Sampling)

![Combination (Over and Under) Sampling](https://user-images.githubusercontent.com/87731897/147422985-9f73195a-5dcb-401e-86f8-4303062ed20b.png)

### UnderSampling

![Undersampling](https://user-images.githubusercontent.com/87731897/147423098-1aa43221-9ca6-4393-9a51-3aa67e6a7ed2.png)

