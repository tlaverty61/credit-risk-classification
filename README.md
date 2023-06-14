# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
-   The purpose of this analysis is to create and evaluate the accuracy of a data model that predicts the credity worthiness of potential borrowers from peer-to-peer lending services

* Explain what financial information the data was on, and what you needed to predict.


* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).


* Describe the stages of the machine learning process you went through as part of this analysis.


* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

-   Balanced Accuracy Score: 95.20% --> this means that when taking into account the sensitivity (recall and/or true positive rate) and specificity (true negative rate) of the model, the balanced prediction accuracy was 95.2% 

-   Precision Score: 92% --> This means 92% of predicted positives were correct

-   Recall Score: 95% --> this means that the model was 95% precise in measuring true positive values our of all positive predictions made


* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
If you do not recommend any of the models, please justify your reasoning.

-   I would recommend using this model to predict the creditworthiness of borrowers, because it has over 95% accuracy in predicting the outcome of the repayment of the initial loan. That accuracy range could be easily molded into a business risk profile to ensure sufficient capital flow for the lenders to remain in business/make a profit.