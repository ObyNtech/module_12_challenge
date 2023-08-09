# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## The purpose of this analysis is to evaluate borrowers to determine healthy and high risk borrowers to deduce which borrower is credit worthy. The analysis leverage dataset from historic lending activity and predicts loan status of different borrowers.The different stages of the machine learning process applied in this analysis are as follows:
1) From the dataset provided, define the label and the freatures.
2) Then split the data into training and testing dataset - This implies some of the dataset will be used to train the model and the test dataset will be used to test the model. 
3) Using the training dataset fit the logistic regression model.
4) Make a predition using the test data.
5) Evaluate the performance of the model as the final step.



Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  
  For this model the accuracy 94%, the average total precision and recall for this model is 99%


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

  For this model the accuracy is quite higher at 99%, the average total precisio and recall for this model is 100%
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

Based on the result of the analysis, I would recommend Model 2 given that it has a higher balanced accuracy score of 99%. This model also have a higher avg total precision of 100%.
For this use case it is more important to predict the the "1" which is the high risk loan. Given that the problem we ar trying to solve is to evalute creditworthyness and borrowers that may be high risk.