# Fake news detection
Implements a fake news detection program using classifiers for Data Mining course at UoA.

## Description
The project is the categorization of text data by news
articles and specifically the detection of fake news. The data contains 2 files in csv format (Fake.csv, True.csv)

## Data Preprocessing
Removed punctuation and made all letters uniform after dropped every null row

## Feature Extraction
To analyse the preprocessed data it has to be represented in a numeric format by using:
* Bag of Words - one of the simplest word embedding approaches
* TF-IDF is a bag words that applies a regularization algorithm.
* Word vectors from Word2Vec model to create a vector representation for a sentence.

## Classifiers
For every of the following classifiers there is a detailed analysis in the pytorch file
* Logistic Regression
* Naive Bayes
* Support Vector Machine
* Random Forests
* Voting Classifier

## Metrics
We evaluate performance of each method in test data using the following evaluation metrics:
* Accuracy score
* F1 score which is the weighted average of precision and recall and thus it is used especially for uneven class distribution problems.

## Contributors
[Apostolos Karvelas](https://github.com/TollisK)

[Ioannis Papadimitriou](https://github.com/Giannis-Papadimitriou)
