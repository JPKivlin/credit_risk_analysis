# credit_risk_analysis

## Overview of analysis
The purpose of this analysis is to apply several machine learning techniques to assess credit card risk.  Six machine learning models were performed with the results shown in the below section.

## Results

The following ML Models were performed.  Below are the balanced accuracy scores:

-[Naive Random OverSampling](Resources/naive.png)
-[SMOTE Oversampling](Resources/smote_oversampling.png)
-[Undersampling Cluster Centroids](Resources/clustercentroids.png)
-[SMOTEENN Combination Sampling](Resources/smoteenn.png)
-[Balanced Random Forest Classifier](Resources/balanced.png)
-[Easy Ensemble AdaBoost Classifier](Resources/easy.png)

## Summary
In summary, 6 different ML models were created with varying results.  Based on these results it is recommended that Smoteenn Comnination Sampling be used as that model takes into account both over and under sampling providing a mix of both techniques.