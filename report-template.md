# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
the purpose was to determine if the Logistic Regression can accurately predict the healthy loans compared to the high risk loansusing the original data set over the resampled data.
* Explain what financial information the data was on, and what you needed to predict.
loan_status is the prediction
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
original
value_counts
0   75036
1    2500

oversampled
0    56271
1.   56271
* Describe the stages of the machine learning process you went through as part of this analysis.
Prpeare the data, then separated the sata into columns specifying X and y as the outcome labels.Created a train_tes_split. The picked the model for classification which is LogisticRegression and fit the model with training data. The model was used to make predictions witht he test data to be evaluated. The predictions were evaluated by comparing metrics, confusin matrix and the classification report.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
SKLearn LogisticRegression
train_test_split
confusion_matrix
classification_report
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 
  * Accuracy: .99
  * Precision Class0: 1.00, Class 1: .85
  * Recall Class0: .99, Class 1: .91



* Machine Learning Model 2:
   * Description of Model 2 
  * Accuracy: .99
  * Precision Class0: 1.00, Class 1: .84
  * Recall Class0: .99, Class 1: .99
  
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
In conclussion both the precision and recall resulted to be really high amd the Logistic Regression model performed well.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
When attempting to gather accurate information the Class 1 resulted a precision of .84 and a recall 0f .91 leaving a gap in the data and creating a false positive.
If you do not recommend any of the models, please justify your reasoning.
