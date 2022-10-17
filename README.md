# Credit_Risk_Analysis

## Overview

The Credit Risk Analysis attempts to evaluate credit risk of customers using six different machine learning models. The algorothms that are used in this analysis are: 
- Cluster Centroids Undersampling
- Combination Sampling
- SMOTE Oversampling
- Native Random Oversampling
- Balanced Random Forest Classifier
- Easy Ensemble AdaBoost Classifer

With the latter being bias reduction models. Following the results, each supervised learning algorithm's accuracy levels as well as F-scores were compared to determine the best algorithm to use for the given credit risk dataset. 


## Results 

### Learning Model 1 - Cluster Centroids Undersampling
- Accuracy score: 0.5295
- F-score average: 0.56
- F-score for high-risk prediction: 0.01

<img width="699" alt="1ccu" src="https://user-images.githubusercontent.com/107447038/196071264-f129eb25-9e23-431c-b7eb-78fd01ce3f59.png">


### Learning Model 2 - Combination Sampling
- Accuracy score: 0.65
- F-score average: 0.72
- F-score for high-risk prediction: 0.02
<img width="697" alt="2" src="https://user-images.githubusercontent.com/107447038/196071302-f8d336c2-4849-4e51-822b-68380e89adc7.png">


### Learning Model 3 - SMOTE Oversampling
- Accuracy score: 0.66
- F-score average: 0.80
- F-score for high-risk prediction: 0.02
<img width="701" alt="3" src="https://user-images.githubusercontent.com/107447038/196071314-5db87d03-93bd-4d56-a0fb-500995bbe4c2.png">


### Learning Model 4 - Naive Random Oversampling
- Accuracy score: 0.67
- F-score average: 0.76
- F-score for high-risk prediction: 0.02
<img width="704" alt="4" src="https://user-images.githubusercontent.com/107447038/196071330-0f030e7e-ef39-4fe0-8d04-9e93f6fd0488.png">


### Learning Model 5 - Balanced Random Forest Classifier
- Accuracy score: 0.76
- F-score average: 0.92
- F-score for high-risk prediction: 0.06
<img width="702" alt="5" src="https://user-images.githubusercontent.com/107447038/196071332-9fa5ee1b-63ec-4965-b7b7-8c94098dc8f6.png">


### Learning Model 6 - Easy Ensemble AdaBoost Classifer
- Accuracy score: 0.93
- F-score average: 0.97
- F-score for high-risk prediction: 0.16
<img width="697" alt="6" src="https://user-images.githubusercontent.com/107447038/196071338-fd331803-7bd9-4de2-a3cc-1a5850c74049.png">

## Summary
From best results (accuracy score & F-scores) to worst:
- Easy Ensemble AdaBoost Classifier (93%)
- Balanced Random Forest Classifier (76%)
- Naive Random Oversampling (67%)
- SMOTE Oversampling (66%)
- Combination Sampling (65%)
- Cluster Centroids Undersampling (53%)

### Recommendations?

One would say that out of the six different algorithms used, the Easy Ensemble AdaBoost Classifier shows the highest accuracy with its 93%, compared to the others which are all under 90%. It is important to note that it also has the highest F-score for high risk predictions, sitting at 0.16 compared to the average F-score across all the algorithms, which is 0.05 (with mode being 0.02). However, 0.16 is still a relatively low F-score, and it would be recommended to explore other algorithms and datasets prior to committing to the Easy Ensemble AdaBoost Classifier for real-life applications of credit risk assessment. 
