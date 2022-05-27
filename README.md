# Random forest regression
Random forest is a supervised learning algorithm which uses ensemble learning method for classification and regression.
Ensemble learning method is a technique that combines predictions from multiple machine learning algorithms to make a more accurate prediction. Random forest is a bagging (Bootstrap Aggregation) technique and not a boosting technique.
Bootstrap Aggregation refers to random sampling with replacement. Bootstrap allows us to better understand the bias and the variance with the dataset. Bootstrap involves random sampling of small subset of data from the dataset. It is a general procedure that can be used to reduce the variance for those algorithm that have high variance. Bagging makes each model run independently and then aggregates the outputs at the end without preference to any model.
Random forest operates by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees.
Advantages of Random Forest:
o	It runs efficiently on large databases.
o	It can handle thousands of input variables without variable deletion.
o	It gives estimates of what variables that are important in the classification.
o	It can estimating missing data and maintains accuracy when a large proportion of the data are missing.
