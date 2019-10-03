## Breast cancer detection

The objective is to come up with a ML classifier/model that would correctly classify a given breast tumor based on its features into corresponding malignant v.s. nonmalignant target output categories.

Based on the breast cancer dataset from Breast Cancer Wisconsin (Diagnostic) Data Set, multiple different machine learning models (decision tree, random forest, SVM with linear kernel, SVM with kernel transform, and linear regression model) are built based on the data with some of the data are split into training set and test set in order to ensure the models can generalize well to the real world data. The results are measured in terms of our objective and quantify using accuracy.

Exploratory Data Analysis and Feature Engineering are conducted before actual construction of the model in order to ensure features that contribute to distinct categorical difference are selected.

Among all the ML algorithm, random forest provides the highest accuracy (98.6%) compared to the rest of the ML models. Further validation of the accuracy using precision and recall suggest that such accuracy prediction is correct (99%). This is expected since for small-to-medium structured/tabular data, decision tree-based algorithms tend to offer superior performance compared to other ML algorithm, while ensemble technique would further enhance the accuracy of the model by taking a weighted output of weaker classifier to make a stronger classifier.

Data: http://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28diagnostic%29
