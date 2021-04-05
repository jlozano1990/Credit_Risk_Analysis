# Credit_Risk_Analysis
## Overview
The purpose of this analysis is to train and evaluate different machine learning models to predict credit risk. Because credit risk is an inherently unbalanced classification problem (this is due to the fact that good loans easily outnumber risky loans), we employed different techniques to train and evaluate models with unbalanced classes by using resampling.

## Results
### Naive Random Oversampling
- **Accuracy Score:** 58%
- **Precision Score:** 99%
- **Recall Score:** 66%

![Naive Random Oversampling Image](https://github.com/jlozano1990/Credit_Risk_Analysis/blob/main/Images/Naive_random_oversampling_results.PNG)

### SMOTE Oversampling
- **Accuracy Score:** 57.5%
- **Precision Score:** 99%
- **Recall Score:** 68%

![SMOTE Oversampling Image](https://github.com/jlozano1990/Credit_Risk_Analysis/blob/main/Images/SMOTE_oversampling_results.PNG)

### Undersampling
- **Accuracy Score:** 57.5%
- **Precision Score:** 99%
- **Recall Score:** 47%

![Undersampling Image](https://github.com/jlozano1990/Credit_Risk_Analysis/blob/main/Images/Undersampling_results.PNG)

### Combination over and under sampling
- **Accuracy Score:** 64%
- **Precision Score:** 99%
- **Recall Score:** 58%

![Combo Image](https://github.com/jlozano1990/Credit_Risk_Analysis/blob/main/Images/combo_over_and_under_sampling_results.PNG)

### Balanced Random Forest Classifier
- **Accuracy Score:** 78%
- **Precision Score:** 99%
- **Recall Score:** 88%**

![Balanced random forest Image](https://github.com/jlozano1990/Credit_Risk_Analysis/blob/main/Images/balance_random_forest_results.PNG)

### Easy Ensemble AdaBoost Classifier
- **Accuracy Score:** 93%
- **Precision Score:** 99%
- **Recall Score:** 93%**

![Easy ensemble AdaBoost Image](https://github.com/jlozano1990/Credit_Risk_Analysis/blob/main/Images/Easy_ensemble_AdaBoost_results.PNG)

## Summary
All of the machine learning models had high precision rates, although many of them were not able to produce as good recall rates. All the models that were primarily trained by oversampling never had a higher accuracy rate than about 60%, so I wouldn't recommend one of those models to use to predict credit risk analysis. Using combination over and under sampling produced a better accuracy result, although it was not a significant improvement. Using a balanced random forest classifier gave us significantly better results when it came to accuracy and recall. The machine learning model that performed the best, and by far, however, was the Easy Ensemble AdaBoost classifier. It had an accuracy  and recall of 93% and a precision rate of 99%. The Easy Ensemble AdaBoost classifier is definitely the machine learning model that I would rexomment to tu use to predict credit risk analysis.
