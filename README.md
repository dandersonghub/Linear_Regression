# Logistic Regression(https://github.com/dandersonghub/Logistic_Regression/blob/main/Logistic_Regression.ipynb)
A logistic regression classification model was built to predict cigarette smokers based on 20 health-related predictor variables. First, all missing values were imputed, normalized, and the dataset was split into training and testing datasets for modeling. Next, the model was fit to the datasets, class weights were adjusted to account for imbalanced data, and probability estimates were calculated. The confusion matrix was used to visually display the binary classifier's ability to correctly predict the classes (1=smoker, 0=nonsmoker). 

Out of all the people that the model predicted would be a smoker, only 60% were. Out of all the people who were true smokers, the model only predicted this outcome correctly for 67% of those people. The average accuracy for this logistic regression classifier is 68%. Based on the model accuracy and AUC (Area Under the Curve) (0.75) of this classifier, I recommend using an alternative classification model to obtain higher accuracy. The following techniques should be explored to find a better performing model; comparing other classification algorithms, oversampling/under sampling, decision threshold moving, and additional parameter tuning.

### Confusion Matrix
![](https://github.com/dandersonghub/Logistic_Regression/blob/main/conf.png)
