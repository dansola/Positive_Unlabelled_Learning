# Positive Unlabelled Learning

In this repo I outline an example of Positive Unlabelled Learning.  I created this example after reading a paper by Elkan and Noto entitled "Learning classifiers from only positive and unlabeled data".  

This methodology is useful when one encounters a dataset with labelled positive examples and a collection of unlabelled examples which could either be positive or negative.

In this Jupyter Notebook I create synthetic data with positive and negative examples.  I then relabel all negative examples and a proportion of the positive examples as 'unlabelled'.  This will allow us to see how well a Positive-Unlabelled classifier works as we can compare the results with the original ground truth labels.

The cool thing about this methodology is that it can be applied to any classifier that outputs a probability.  In this example I use a simple linear regression classifier.
