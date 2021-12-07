# ML-Iris-Dataset-Models
This repository contains a comperative evaluation of machine learning algorithms given the problem of classifying flowers based on lenghts and breadths of sepals and petals of a flower. 

It is a relatively simple dataset so ultimately a wide range of data visualization could be provided and not much preprocessing was required.

This repository solves the classification problem by using the most popular classification algorithms available on SciKit Learn.

Here the models have been compared using cross_val_score which in essence executes the algorithm a specific number of times and computes the mean and standard deviation of results.

Box plots of the results obtained from cross_val_score have also been provided for thorough comparison.

Comments on the results:
1. The comparisons of the mean and box plots showed SVM (Support Vector Machine) as the best classifier for use which ended up getting an accuracy of around 96% with a single wrong prediction.
2. Individual testing of other models with and without hyperparameter tuning seemed to agree with the results of the model comparison.
3. Expectedly, when Decision Tree algorithm was used with hyperparameter tuning, the results did not improve.
4. However, using Decision Tree algorithm without hyperparameter tuning gave the best accuracy of 100%. This result was quiet unexpected to me personally.

Based on the findings of the experiment, I conclude and ultimately realize that a machine learning algorithm should be tailored to the data it is going to train on. Comparing algorithms side-by-side is not enough and insight of the type of data and the nature of the algorithm is very important to create the perfect data-algorithm pair.
