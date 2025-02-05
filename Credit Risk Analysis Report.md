# credit-risk-classification

## Credit Risk Analysis Report

### Overview of the analysis:
**Purpose**:
* evaluating of a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.and
* evaluating the performance of the LogisticRegression model using confusion matrix and classification report that if this model is recommended for the company to use.
* predicting based on the the loan status of the borrowers.
the data is spliting to the labels or the target and assign to 'y' variable to the "loan status" column.and 'x' variable to other features of dataset.
i use the logisticRegression model for the prediction of the "x_test" based on the company that "0" is healthy loan and "1" is high risk loan.
the model is fit to the "y-train" and "x_train" and predicted the "x_test" based on the labels of the loan status "0" and "1".

**Results**: 
* based on the givin dataset and using the logisticregression model.here is the list of the result
* Accuracy score:it is the ratio of correctly predicted observations to the total number of observation. the result for the given dataset is 99%(0.99)
* Precision score:it is the ratio of correctly predicted positive observations to the total predicted positive observations. the result for the given dataset is 100% or (1)
*  Recall: the ratio of correctly predicted positive observations to the total predicted observation.the result for the given dataset is 100% or (1)
  
**Summary**:
 * the result from the machine learning model;the classification is to be considered as accurate and precise.the result from the confusion matrix the aggregate sums of the column and row are all the same.n=19384.
* classification report:the classification model report; that the model predicted 100 of the health loan or '0' on both precision and recall.and also predicted the high risk loan or '1' 87% of precision and 95% of the recall .
  the room for the error is very small having the accuracy of over 99% and 100% of precision and  recall.very small room for the false negetive and false positive.
 
* I conclude and recommend that the company can use this classfication model('LogisticRegression') to identify the creditworthiness of the borrowers.

