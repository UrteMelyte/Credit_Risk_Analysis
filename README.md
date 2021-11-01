# Credit_Risk_Analysis

## Overview of the analysis
We utilized supervised machine learning to determine credit card risk, running through various algorithms to determine the best suited one for the data.

## Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
### Naive Random Oversampling
Balanced Advanced Score: **0.649**

![logistic](https://user-images.githubusercontent.com/86527135/139562711-3868cb45-aa6b-4d0b-83bd-6b8effbe4e75.PNG)

### SMOTE Oversampling
Balanced Advanced Score: **0.658**

![smote](https://user-images.githubusercontent.com/86527135/139562716-9692ccc9-75f7-41fa-b358-26dfe3acf87b.PNG)

### Cluster Centroids Undersampling
Balanced Advanced Score: **0.544**

![clustercentroids](https://user-images.githubusercontent.com/86527135/139562712-11712698-8111-453c-81f4-44fb8f98baee.PNG)

### Combination (Over & Under) Sampling
Balanced Advanced Score: **0.648**

![combo](https://user-images.githubusercontent.com/86527135/139562722-c17004d5-cccf-4616-a8b4-2935e8058841.PNG)

### Random Forest Classifier
Balanced Advanced Score: **0.788**

![randomforest](https://user-images.githubusercontent.com/86527135/139562723-28c7234f-3e5f-40f3-b806-97d81e0c7deb.PNG)

### Easy Ensemble Classifier
Balanced Advanced Score: **0.931**

![easyensemble](https://user-images.githubusercontent.com/86527135/139562725-e5e15703-190c-4299-ba80-4f2b187ee2fd.PNG)

## Summary
Out of the resampling methods, undersampling had the lowest balanced accuracy score, with SMOTE proving most reliable. When including ensemble classifiers, Easy Ensemble's report surpassed all other methods. Due to this, Easy Ensemble is the recommendation.
