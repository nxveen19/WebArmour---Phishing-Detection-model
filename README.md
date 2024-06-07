# Phishing URL Detection 
![image](https://app.gemoo.com/share/image-annotation/657656297930956800?codeId=DGYwd3EJjza7O&origin=imageurlgenerator&card=657656295548600320)


## Phishing URL Detection
Introduction
The internet has become an integral part of our lives, but it also provides opportunities for malicious activities like phishing. Phishing involves deceiving victims, often through social engineering or mockup websites, to steal sensitive information such as account credentials. While various methods have been proposed to detect phishing websites, machine learning has emerged as one of the most effective approaches. Phishing attacks often exhibit common characteristics that can be identified using machine learning algorithms.

# Contents
This repository contains a Python notebook (phishing_detection.ipynb) that demonstrates the process of detecting phishing URLs using machine learning. The notebook covers the following steps:

Loading the dataset
Exploratory Data Analysis (EDA)
Visualizing the data
Splitting the dataset into training and testing sets
Building and training machine learning models
Comparing the performance of different models
Dependencies
The following Python libraries are required to execute the code:

numpy
pandas
matplotlib
seaborn
sklearn
warnings
catboost
xgboost
Dataset
The dataset used in this project (phishing.csv) contains information about various URLs, including features such as prefix/suffix, number of subdomains, use of HTTPS, presence of anchor tags, and website traffic. The dataset also includes a target variable indicating whether a URL is classified as phishing or not.

# Model Building
The notebook demonstrates the training of multiple machine learning models for phishing URL detection. The models considered are:

Logistic Regression
k-Nearest Neighbors
Support Vector Classifier
Naive Bayes
Decision Tree
Random Forest
Gradient Boosting
CatBoost
XGBoost
Multilayer Perceptrons
Model Evaluation
The performance of each model is evaluated using the following metrics:

# Accuracy
F1 score
Recall
Precision
The classification report for each model is also provided, offering a detailed breakdown of performance metrics for phishing and non-phishing URLs.

# Results
A summary of the model performance is presented in tabular format, listing the accuracy, F1 score, recall, and precision for each model. The results are sorted based on accuracy and F1 score, providing insights into the most effective models for phishing URL detection.

## Conclusion
The notebook concludes with a comparison of model performance and suggestions for further improvements or experimentation.
