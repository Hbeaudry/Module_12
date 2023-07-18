# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

The purpose of the analysis was to see if there was a more accuracte way of predicting if the loans in the original data set were healthy vs high risk through the use of creating a logistic regression machine learning model to analyse the dataset. Through this analysis, I was trying to predict was the loan_status to determine if the the loans were a healthy risk or high risk.

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

Model 1 Accuracy: 99%
Model 1 Precision: 99%
Model 1 Recall: 99%

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

Model 2 Accuracy: 99%
Model 2 Precision: 99%
Model 2 Recall: 99%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

The 2nd model performed better, specifially on Recall scores when it came to high risk loans by 8%. I believe that performance does depend on the problem we are trying to solve. This model would need to be used on a new set of loan data to see if the accuracy is similar to the results on the data set used in this analysis.

If you do not recommend any of the models, please justify your reasoning.
