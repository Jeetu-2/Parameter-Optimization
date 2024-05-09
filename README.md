# Parameter-Optimization for SVM

This project demonstrates the optimization of Support Vector Machine (SVM) on the Dry Bean dataset obtained from the UCI Machine Learning Repository. The dataset contains instances of seven different varieties of dry beans, with 16 features describing each instance.


## Dataset
The Dry Bean dataset consists of 13611 instances, with each instance having 16 features. The dataset is divided into 10 different samples for training and testing.

## Implementation
1. Loading the Dataset:
The dataset is loaded from a CSV file using the pandas library.

2. Splitting the Dataset:
The dataset is split into training and testing sets with a 70-30 ratio, repeated 10 times to get 10 different samples.

3. Optimizing SVM:
SVM is optimized for each sample using cross-validation with 100 iterations. GridSearchCV is used to find the best hyperparameters.

4. Recording Results:
The best parameters and accuracies are recorded for each sample. The sample with maximum accuracy is identified.

5. Convergence Graph:
A convergence graph is plotted for the sample with the maximum accuracy, showing how the training and testing accuracies change over iterations during the optimization process.
