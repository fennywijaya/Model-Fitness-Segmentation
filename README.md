# Model Fitness Segmentation

### Introduction
Model Fitness, a fitness center franchise is developing a customer engagement strategy based on analytical data. This project will analyze fitness center customer profiles from a dataset containing customer churn rate data for a given month and information about the previous month.

### Objectives
* Learn how to predict the churn probability (for the next month) for each customer.
* Creating user segmentation by selecting the most dominant group, and describing the main characteristic.
* Analyze the factors that influence churn the most.
* Identify targeted groups.
* Recommend steps to reduce churn.
* Describe other patterns related to customer interactions.
* Draw basic conclusions
* Provide recommendations or strategies to improve customer retention.

### Steps
* Data pre-processing
* Exploratory Data Analysis
* Binary Classification Model
* Create User Clusters 
    * Data standardization
    * Plotting dendrogram
    * KMeans clustering
    * Calculating churn rate in each cluster

### Libraries Used
* Pandas
* Numpy
* Matplotlib, Seaborn
* scipy.stats (chi2_contingency)
* sklearn.model_selection (train_test_split)
* sklearn.linear_model (LogisticRegression)
* sklearn.ensemble (RandomForestClassifier)
* sklearn.preprocessing (StandardScaler)
* sklearn.metrics (accuracy_score, precision_score, recall_score, f1_score)
* sklearn.cluster (KMeans)
* scipy.cluster.hierarchy (dendrogram, linkage)
