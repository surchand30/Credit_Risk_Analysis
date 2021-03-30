# Credit_Risk_Analysis

## Overview : 
This analysis is being performed to help LendingClub predict and classify a loan as a good loan vs a risky loan using different classification techniques.

### Purpose: 
Using different sampling techniques, we are trying to understand which technique is going to be the most effective in terms of precision and sensitivity to classify a loan. Higher the models sensitivity, higher the chances of accurately determining a risky loan vs a good loan.

### Results: As part of this analysis, six random sampling algorithms were employed

1) Naive Random Oversampling :

![Naive Random Oversampling](https://github.com/surchand30/Credit_Risk_Analysis/blob/main/images/Naive%20Random%20Oversampling.PNG)

Balanced Accuracy Score : 0.66

Precision : 0.01

Sensitivity : 0.66

2) SMOTE Oversampling :

![SMOTE oversampling](https://github.com/surchand30/Credit_Risk_Analysis/blob/main/images/SMOTE%20Oversampling.PNG)

Balanced Accuracy Score : 0.63
Precision : 0.01
Sensitivity : 0.62

3) Undersampling:

![Undersampling](https://github.com/surchand30/Credit_Risk_Analysis/blob/main/images/Undersampling.PNG)

Balanced Accuracy Score : 0.59
Precision : 0.01
Sensitivity : 0.61

4) Combination of Over and Undersampling:

![Over and Under Sampling](https://github.com/surchand30/Credit_Risk_Analysis/blob/main/images/Combination%20of%20Over%20and%20Undersampling.PNG)

Balanced Accuracy Score : 0.66
Precision : 0.01
Sensitivity : 0.74

5) Balanced Random Forest Classifier:

![Balanced Random Forest Classifier](https://github.com/surchand30/Credit_Risk_Analysis/blob/main/images/Balanced%20Random%20Sample%20classifier.PNG)

Balanced Accuracy Score : 0.78
Precision : 0.04
Sensitivity : 0.67

6) Easy Ensemble Classifier:

![Easy Ensemble Classifier](https://github.com/surchand30/Credit_Risk_Analysis/blob/main/images/Easy%20Ensemble%20Classifier.PNG)

Balanced Accuracy Score : 0.93
Precision : 0.07
Sensitivity : 0.91
