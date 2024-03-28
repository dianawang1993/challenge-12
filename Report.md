## Overview of the Analysis

The lending company lends fund to the borrowers with the expectation that the borrower will pay back the fund. Credit risk associated if the borrower cannot return the fund or repaying a loan causing the loss for the lender. That the reason why the lending company using the models to analyze and identify a borrower's creditworthiness.

    # By using models, it help lending company to determine which loans are healthy(low-risk) or nonhealth(high-risk) loan.

    The Logistic Regression Algorithm is the good tool to use to predict the probability of target variable in classification problems.
    Using the dataset provided by the lending company, the logistic regression model with an accuracy score of 95%. Although the accuracy of the model is high, the model recall value for non-health loans (0.91) is lower than the recall value for healthy loans (0.99). This indicates that the model predicts the loan status as healthy rather than predicting the loan status as unhealthy. This is due to an imbalanced dataset, which means that most of the data falls into one category of labels (in this case, healthy loans far outnumber non-health loans).

    According to the confusion matrix in step 3

    Out of the 18,765 healthy (low-risk) loan statuses, the model correctly predicted 18,663 healthy loan statuses and incorrectly predicted 102 healthy loan statuses.

    Out of the 619 unhealthy (high-risk) loan statuses, the model correctly predicted 563 as unhealthy and incorrectly predicted 56 as unhealthy.

## Results

The logistic Regression model:

According to the models recall scores, the model made 1% of mistakes when predicting healthy loans and made 9% of mistakes when predicted non-healthy loans. However, the model generated an accuracy score of 95% but could be improved due to the dataset being imbalanced.

Logistic Regression Model fitted with Balanced (oversampled)

According to the models recall scores, the model made 1% of mistakes when predicting healthy loans and made 1% of mistakes when predicted non-healthy loans.
The model generated an accuracy score of 99% due to the dataset being balanced.

## Summary

Lending companies may need a model that identify healthy loans from non-healthy loans in most cases. The logistic regression model fitted with OverSampled data performed much better than the model fitted with unbalanced data because the data was balanced and produced higher accuracy scores and higher recall rates, indicating that the model was better. Lending companies will most likely want to reduce false positives because there is a good chance that the lender will lose the funds provided when classifying a non-health loan as a healthy loan. 

