# Kernel PCA

In our dataset, wine.csv, each row corresponds to a different kind of wine.
And for each of these wines, we have a set of features from the alcohol level to the proline.
We also have the customer segment, which is the segment of customers
to which the wine belongs to, in the sense that all the customers of each segment(we have three segments in total) have the same preference for such wines.
And now the challenge is to build a logistic regression model combined to some dimensionality reduction
techniques applied to this dataset so that we can end up with a less complex data set, which at the
same time will provide an excellent way for the logistic regression model to learn the correlations
between all these features and the dependent variable.
And then for each new wine, we will deploy this predictive model to predict the customer segment to
which this wine belongs, so that the owner of the wine shop can recommend each new wine to the right customer.