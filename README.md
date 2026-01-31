# scoring-parameters-in-cross-val-score-function-in-scikit-learn-ML-
cross val score is a function in scikit learn to evaluate ML models.

cross\_val\_score is a function from **scikit-learn** used to evaluate the performance of a machine learning model using cross-validation.



Instead of testing a model on a single train–test split, it:



* Splits the dataset into multiple folds
* Trains the model multiple times
* Evaluates it on different validation sets
* Returns multiple performance scores



This gives a more reliable and unbiased estimate of model performance.



**How to implement:**



from sklearn.model\_selection import cross\_val\_score

scores = cross\_val\_score(estimator, X, y, scoring=None, cv=5, n\_jobs=None)







