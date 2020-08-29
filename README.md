# Kaggle-Competition-Santander-Customer-Transaction-Prediction
URL: https://www.kaggle.com/c/santander-customer-transaction-prediction


## Description
At [Santander](https://en.wikipedia.org/wiki/Santander_Bank) our mission is to help people and businesses prosper. We are always looking for ways to help our customers understand their financial health and identify which products and services might help them achieve their monetary goals.

Our data science team is continually challenging our machine learning algorithms, working with the global data science community to make sure we can more accurately identify new ways to solve our most common challenge, binary classification problems such as: is a customer satisfied? Will a customer buy this product? Can a customer pay this loan?

In this challenge, we invite Kagglers to help us identify which customers will make a specific transaction in the future, irrespective of the amount of money transacted. The data provided for this competition has the same structure as the real data we have available to solve this problem.


## Evalutaion
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

**Submission File**
For each Id in the test set, you must make a binary prediction of the target variable. The file should contain a header and have the following format:
```
 ID_code,target
 test_0,0
 test_1,1
 test_2,0
 etc.
```


## File descriptions
1. train.csv - the training set.
2. test.csv - the test set. The test set contains some rows which are not included in scoring.
3. sample_submission.csv - a sample submission file in the correct format.
