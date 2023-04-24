# ML_projects_on_own_language_learning_dataset
This repository contains all of my ML projects done with use of my own language learning data set; the data set is a time series with the number of minutes spent learning  each day from March 2019 until November 2022.

1)First project - classification

The main file containing EDA, data preparation and models development can be found here:
https://github.com/OlgaMCgithub/ML_projects_on_own_language_learning_dataset/blob/main/recall_metric_binary_classification_lang_analysis_0-1%20target.ipynb

The excel files compose the dataset used for model training and the pkl files are serilized developed models ready for reuse on unseen data.

In this project, among others, I used: 
DBSCAN, LogistingRegression, SVM, XGBoost, AdaBoost, histograms, boxplots, time series plots, standard scaler, PCA, KBest, pipelines, GridSearchCV,  validation curves, pickle,
metrics: recall, roc_auc, precision, confusion matrix, classification report, VotingClassifier etc.

2)Second project - clustering

The main file containing EDA, data preparation, hyperparameter tuning, cluster visualisation and analysis can be seen here:
https://github.com/OlgaMCgithub/ML_projects_on_own_language_learning_dataset/blob/main/clustering.ipynb

In this project, among others, I used: 
DBSCAN, K-Means, Agglomerative clustering, histograms, boxplots, time series plots, standard scaler, pipeline, Silhouette score, Davies-Bouldin score, elbow method for founding n-clusters, 3-d plots of clusters, pairplots
