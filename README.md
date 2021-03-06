# Positive Unlabelled Learning

In this repo I outline an example of Positive Unlabelled Learning.  I created this example after reading a paper by Elkan and Noto entitled "Learning classifiers from only positive and unlabeled data".  

This methodology is useful when one encounters a dataset with labelled positive examples and a collection of unlabelled examples which could either be positive or negative.

In this Jupyter Notebook I create synthetic data with positive and negative examples.  I then relabel all negative examples and a proportion of the positive examples as 'unlabelled'.  This will allow us to see how well a Positive-Unlabelled classifier works as we can compare the results with the original ground truth labels.

The cool thing about this methodology is that it can be applied to any classifier that outputs a probability.  In this example I use a simple linear regression classifier.

The paper can be found [here](https://dl.acm.org/doi/abs/10.1145/1401890.1401920).

Elkan, C., & Noto, K. (2008, August). Learning classifiers from only positive and unlabeled data. In Proceedings of the 14th ACM SIGKDD international conference on Knowledge discovery and data mining (pp. 213-220).
