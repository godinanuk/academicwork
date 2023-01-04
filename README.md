# machinelearning-telecomchurn
Machine learning models for telecom churn

This program will give you a glimpse of different algorithms / models, we can use for classification problem. Please note that we might see more algorithms which I haven't used or covered.  I have tried many or most of them but only included the ones which had earned their position for the dataset I have used.

Note: As the dataset file is larger than allowed sizes, I could not add full dataset.  I have uploaded a shorter version.

For telecom churn problem recall ratio is very important as we do not want to miss out any customer who is about to churn.

In terms of run time taken by different algorithms:
1. Logistic Regression and Decision Trees took less than a second.  Logistic Regression results were good, but Decision trees overfitted.
2. MLP Classifier, AdaBoost Classifier, Ridge Classifier, LinearDiscriminantClassifier, Neural Networks, QuadraticDiscriminantAnalysis, Light GBM took less than a minute.  Results of MLP Classifier, AdaBoost Classifier, Ridge Classifier, LinearDiscriminantClassifier were good with good test recall ratios ranging between 76% to 82%.  Ridge Classifier tops with 82% test recall ratio.
3. BaggingClassifier was the most expensive one which took more than 45 minutes. Results of BaggingClassifier was good with 81% of test recall ratio.
4. SGD Classifier and Stacking Classifier took in a range of 3 to 5 minutes, and both classifier's results were good with recall ratio's of 81% and 79% respectively.

Please note results will be different for different datasets and also depends based on feature engineering and feature selection.

