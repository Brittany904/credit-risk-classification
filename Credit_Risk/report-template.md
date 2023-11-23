# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis is to utilize and build a model to identify the credit history and patterns of borrowers. This dataset was on the lending activity as mentioned previously from a lending services company to predict the arrangement of healthy loans versus high risk loans. This data contains columns of information with the loan sizes, the interest rate, the debt to income ratio, the number of accounts, and more. The variable y that was created is what we are trying to predict, the type of loan, and the 'value_counts' is to show the balance of the data we are wanting to predict.
To process this analysis we began with a relevant dataset and breaking down the information into a label(what we are predicting) and a feature(what is used to add relevancy and importance to the decision making). The data was then split into testing and training datasets to be used for a 'LogisticRegression' model, the chosen one for this analysis. After receiving the results of that mdoel, the data was then resampled and that same model was used again.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
    * Accuracy: The accuracy score is 95% which is close to 1 and deems this as correctly identifying the data.
    * Precision: The model for healthy loans has a precision of 1 which has the highest accuracy. For high-risk loans it is only 86% accurate, which is still a higher amount.
    * Recall: For healthy loans the recall score is 99% and for high-risk loans it is 90%, which means this could be a good model.




* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
    * Accuracy: The accuracy score is 95% which is close to 1 and deems this as correctly identifying the data.
    * Precision: The model for healthy loans has a precision of 1 which has the highest accuracy. For high-risk loans it is only 86% accurate, which is still a higher amount.
    * Recall: For healthy loans the recall score is 99% and for high-risk loans it is 90%, which means this could be a good model.


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

Due to the results, this model is not recommended to solve the problem. It is more important to predict the '1''s, as that holds weight with the company's business desicions. Due to the dataset having an imbalance the Linear Regression Model would not be the best and would overfit the dataset. 
