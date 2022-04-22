# Sberbank customer segmentation


## Task description:
One of the most valuable sources of customer information is bank transaction data. In this competition, participants are asked to answer the question: is it possible to predict the gender of a client using information about outcome transactions and income on a bank card? And if so, what is the accuracy of such a prediction?

## Dataset Description:
- types.csv - reference of transaction types
- codes.csv - reference of transaction codes
- transactions.csv - transactional data on banking operations
- train_set.csv - training set with client gender marking (0/1 - client gender) - test_set.csv - no need to use.
transactions.csv columns description:
- client_id - client is id
- datetime -transaction date (format - ordered day number hh:mm:ss - 421 06:33:15) - code - transaction code
- type - transaction type
- sum - sum of transaction


## Part 1, Unsupervised:
I. Explore the dataset. Do the descriptive statistics.

II. Explanatory data analysis. Exploring the features, visualizations etc. (https://
www.kaggle.com/learn/data-visualization, https://towardsdatascience.com/ exploratory-data-analysis-8fc1cb20fd15, https://www.mastersindatascience.org/ learning/what-is-exploratory-data-analysis/ )

III. Feature engineering. Encodings, generating the features from date-time, sum and from other columns. (https://www.kaggle.com/learn/feature-engineering, https:// www.kaggle.com/learn/data-cleaning )

IV. Unsupervised learning. Do the Cluster analysis. Segment the customers. K-means, Hierarchical Clustering. With different metrics, linkages. Visualize the clusters etc. Look for the optimal number of the clusters

V. Analyzing the results.

## Part 2, Supervised:
VI. Supervised learning. Build model for prediction the gender of the clients. Decision Trees, KNN, Random Forest. Tune the hyper parameters, grid search, cross validation etc. Visualization of the models etc..

VII. Analyze models, Result comparison, ROC/AUC, precision and recall curves, deep analyzing.

VIII. Conclusion.
