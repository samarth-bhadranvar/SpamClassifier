This is an implemenation of k-Nearest neighbour algorithm used to filter spam messsages.

Data set used: 
UCI Machine Learning Data repository : Spambase Data Set
http://archive.ics.uci.edu/ml/datasets/Spambase

Contents in the notebook:

1. Implementation of kNN Algorithm to classify messages as spam/ not spam
2. Study of trend of classification accuracies for different values of k (1...100) and selecting the best possible value for k in kNN Algorithm
3. Validation of the filter using K Fold cross-validation
4. Evaluation of results for each fold


Note: For the dataset used and the training/test set ratio set to 0.33, the trend in accuracies show that in  k=4 yeilds the best result in kNN algorithm implementation. This value of k is used during cross validation as well.
