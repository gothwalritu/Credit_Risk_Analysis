## Module 17 

## Credit Risk Analysis

# Overview of the analysis: 

In this module challenge we are predicting the credit risk. We are applying the supervised machine learning to a credit card credit dataset from LendingClub, which is a lending service company. In credit card industry the good loans are much higher in comparison to bad loans. Hence, the credit risk is a classic example of unbalanced classification problem. To tackle the unbalanced classes we are employing different algorithm and libraries to create and evaluate the models:

1.	Imbalanced-learn

2.	Scikit-learn

3.	RandomOverSampler

4.	SMOTE algorithm

5.	ClusterCentroid alsorithms

6.	SMOTEENN algorithm 

7.	BalancedRandomForestClassifier 

8.	EasyEnsembleClassifier 

# Results: 

•	With Naive Random Oversampling technique the balanced accuracy test score is 64%, the precision for the high_risk is 1% and the recall is 69%. The precision for the low risk is 100% and recall is 59%.

![Picture_1](https://github.com/gothwalritu/Credit_Risk_Analysis/blob/main/Screen_shots/Naive's.png)



•	With SMOTE sampling technique the balanced accuracy test score is 64%, the precision for the high_risk is 1% and the recall is 63. The precision for the low risk is 100% and recall is 69%.

![Picture_1](https://github.com/gothwalritu/Credit_Risk_Analysis/blob/main/Screen_shots/SMOTE.png)


•	With Undersampling technique the balanced accuracy test score is 54%, the precision for the high_risk is 1% and the recall is 69%. The precision for the low risk is 100% and recall is 40%.

![Picture_1](https://github.com/gothwalritu/Credit_Risk_Analysis/blob/main/Screen_shots/Undersampling.png)


•	With Combination sampling technique the balanced accuracy test score is 64%, the precision for the high_risk is 1% and the recall is 72%. The precision for the low risk is 100 and recall is 57%.

![Picture_1](https://github.com/gothwalritu/Credit_Risk_Analysis/blob/main/Screen_shots/Combination.png)

•	With Balanced Random Forest Classifier model the balanced accuracy test score is 79%, the precision for the high_risk is 4% and the recall is 67%. The precision for the low risk is 100 and recall is 91%.

![Picture_1](https://github.com/gothwalritu/Credit_Risk_Analysis/blob/main/Screen_shots/Random_Forest.png)

•	With Easy Ensemble AdaBoost Classifier model the balanced accuracy test score is 92%, the precision for the high_risk is 7% and the recall is 91%. The precision for the low risk is 100% and recall is 94%.

![Picture_1](https://github.com/gothwalritu/Credit_Risk_Analysis/blob/main/Screen_shots/Adaboost.png)



# Summary: 

In this module we compared the accuracy scores of four models: Naïve’s Random Oversampling,  SMOTE Oversampling, Undersampling and Combination (over and under sampling). Then we tried two more models: Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier. We found that the accuracy of first four models is not as good as the last two models. We want our model to predict the target values with high accuracy and precision, hence we want a balance of precision and recall which could be delivered by employing ensemble classifier models i.e., Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier. Among the ensemble classifier model Easy Ensemble AdaBoost Classifier model has the highest accuracy and recall score, and therefore I recommend the same model to use over others.
