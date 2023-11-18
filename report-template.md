# Module 12 Report Template

## Results
* Machine Learning Model 1:
The extremum for a balanced accuracy score is 1 and we obtained a value of about 0.95. This means our model is very accurate overall. This is also reflected in the confusion matrix, as we see true positives and true negatives heavily outweigh false positives and false negatives. Finally, precision, recall and f1-scores are quite high across the board, as shown by the classification report.

* Machine Learning Model 2:
The logistic regression model fit with oversampled data performs better than the original model, although not by a significant margin since both models predict the data quite well across the board. Again,the accuracy score, confusion matrix and classification report all show a high level of accuracy.

## Summary
Out of the two models we used, the model fit with oversampled data performed best. I would recommend it given its high level of accuracy, particularly with healthy loans. It can be used to approve loan applications quicker, given how well it predicts this. I do think even if it is pretty accurate with predicting high risk loans, I don't think it should be used to reject loans entirely. There should still be a human involved in that decision. 
