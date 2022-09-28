# Project_Data_Mining_II
Progetto svolto per il corso di Data Mining II (2021-2022)

Project Guidelines

Module 1 - Imbalanced Learning, Dimensionality Reduction, Anomaly Detection
- Explore and prepare the dataset. You are allowed to take inspiration from existing notebooks you can find online and figure out your personal research perspective (from choosing a subset of variables to the class to predict…). You are welcome in creating new variables and performing all the pre-processing steps the dataset needs.
- Define one or more (simple) classification tasks and solve them with Decision Tree and KNN.
- Identify the top 1% outliers: adopt at least three different methods from different families (e.g., density-based, angle-based… ) and compare the results. Deal with the outliers by removing them from the dataset or by treating the anomalous variables as missing values and employing replacement techniques. In this second case, you should check that the outliers are not outliers anymore. Justify your choices in every step.
Analyze the value distribution of the class to predict with respect to point 2; if it is unbalanced leave it as it is, otherwise turns the dataset into an imbalanced version (e.g., 96% - 4%, for binary classification). Then solve the classification task using the Decision Tree or the KNN by adopting various techniques of imbalanced learning.
- Exploit and tests different dimensionality reduction techniques for (i) visualization in two dimensions, (ii) improve classification performance, (iii) improve outlier detection.
- Draw your conclusions about the techniques adopted in this analysis.

Module 2 - Advanced Classification Methods
-Solve the classification task defined in Module 1 (or define new ones) with the other classification methods analyzed during the course: Naive Bayes Classifier, Logistic Regression, Support Vector Machines, Neural Networks, Ensemble Methods, Gradient Boosting Machines and evaluate each classifier with the techniques presented in DM1 (accuracy, precision, recall, F1-score, ROC curve). Perform hyper-parameter tuning phases and justify your choices.
-Besides the numerical evaluation draw your conclusions about the various classifiers, e.g. for Neural Networks: what are the parameter sets or the convergence criteria which avoid overfitting? For Ensemble classifiers how the number of base models impact the classification performance? For any classifier which is the minimum amount of data required to guarantee an acceptable level of performance? Is this level the same for any classifier? What is revealing the feature importance of Random Forests?
-Select two continuous attributes, define a simple linear univariate regression problem and try to solve it using different techniques reporting various evaluation measures. Plot the two-dimensional dataset. Then generalize to multiple linear regression and observe how the performance varies. Solve it using linear regressions, regularized linear regressions (such as Lasso and Ridge) but also machine learning approaches such as Gradient Boosting Machines.

Module 3 - Time Series Analysis
-Prepare a dataset on which you can run time series clustering; motif/anomaly discovery and classification.
-On the dataset created, compute classification with KNN based on Euclidean/Manhattan and DTW distances and compare the results.
-To perform the clustering you can choose among different distance functions and clustering algorithms. Remember that you can reduce the dimensionality through time series approximation. Analyze the clusters and highlight similarities and differences.
-Analyze the dataset for finding motifs and/or anomalies. Visualize and discuss them and their relationship with other features.
-Solve the classification task on the time series dataset(s) and evaluate each result. In particular, you should use shapelet-based classifiers and structural-based classifiers. Analyze the shapelets retrieved and discuss if there are any similarities/differences with motifs and/or shapelets.

Module 4 - Sequential Patterns and Advanced Clustering
-Sequential Pattern Mining: Convert the time series into a discrete format (e.g., by using SAX) and extract the most frequent sequential patterns (of at least length 3/4) using different values of support, then discuss the most interesting sequences.
-Advanced Clustering: On a dataset already prepared for one of the previous tasks in Module 1 or Module 2, run at least one clustering algorithm presented in the advanced clustering lectures (e.g. X-Means, Bisecting K-Means, OPTICS). Discuss the results that you find analyzing the clusters and reporting external validation measures (e.g SSE, silhouette).

Module 5 - Explainability
-Try to use one or more explanation methods (e.g., TREPAN, LIME, LORE, SHAP, Counterfactual Explainers, etc.) to illustrate the reasons for the classification in one of the steps of the previous tasks.

N.B. When “solving the classification task”, remember, (i) to test, when needed, different criteria for the parameter estimation of the algorithms, and (ii) to evaluate the classifiers (e.g., Accuracy, F1, Lift Chart) in order to compare the results obtained with an imbalanced technique against those obtained from using the “original” dataset.
