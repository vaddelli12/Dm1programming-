Assignment Overview

For this task the objective is to classify a dataset using three methods; Naive Bayes Classifier, Support Vector Machine (SVM) and Decision Tree. The dataset comprises images categorized into four classes with classification based on edge histograms derived from these images.

Execution Steps--

Data Preparation;

Utilize images, from all four classes.
Transform the images into edge histograms to represent them as vectors.
Divide the dataset into a training set and a test set with an 80/20 split for each class.
Standardization;

Normalize the training data using mean and variance.
Normalize the test data using the means and variances calculated from the training data.
Model Selection;

Conduct 5 cross validation and stratified 5 fold cross validation on the training set for k Nearest Neighbor Classifiers with varying k values such as 1, 3 5 7, 10 and 20.
Generate error curves for validation and training datasets to assess model complexity, overfitting and underfitting.
Choose the k value that yields the lowest mean validation error, for further assessment.Assessing the Model;

1. Assess the selected k Nearest Neighbor classifier, with the test data. Determine the error rate.
2. Conduct a 5 cross validation on the test set utilizing three different classification techniques; Naive Bayes Classifier, SVM and Decision Tree.
3. Visualize confusion matrices for each method applied to the test set.
4. Compare the effectiveness of these approaches by examining them considering validation accuracies, performance, on the test set and F measure scores.
