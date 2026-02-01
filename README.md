
cross\_val\_score is a function from **scikit-learn** (https://scikit-learn.org/0.18/modules/generated/sklearn.model_selection.cross_val_score.html) used to evaluate the performance of a machine learning model using cross-validation.



Instead of testing a model on a single train–test split, it:



* Splits the dataset into multiple folds
* Trains the model multiple times
* Evaluates it on different validation sets
* Returns multiple performance scores
<img width="885" height="613" alt="image" src="https://github.com/user-attachments/assets/902082fe-d0e3-4c94-8467-f530454ea2f8" />



This gives a more reliable and unbiased estimate of model performance.



**How to implement:**



from sklearn.model\_selection import cross\_val\_score

scores = cross\_val\_score(estimator, X, y, scoring=None, cv=5, n\_jobs=None)







