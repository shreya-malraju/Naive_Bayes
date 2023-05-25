# Naive_Bayes_from_scratch

Naive Bayes is a classification algorithm that is based on Bayes' theorem in probability. The basic idea behind Naive Bayes is to calculate the probability of a data point belonging to each possible class label, and then choose the class label with the highest probability as the predicted label for the data point. This is done by calculating the conditional probability of each feature given each class label, and then combining these probabilities using Bayes' theorem to get the posterior probability of each class label given the features.

DATASET

The 20 Newsgroups dataset consists of a collection of approximately 20,000 newsgroup documents, evenly distributed across 20 different categories such as politics, sports, religion, and computers.

<img width="369" alt="image" src="https://github.com/shreya-malraju/Naive_Bayes_from_scratch_Text_Classification/assets/132793649/487312ae-b3ee-4156-84af-e910228ffa1c">

The goal of text classification using Naïve Bayes on the 20 Newsgroups dataset is to automatically assign each document to its corresponding category based on its content.

The dataset used is a collection of 20 newsgroups, each containing 1,000 documents. In this project we need to classify all the text documents from the given data set. And then the data set should be Split into 50 % as testing data and the other half as training data and after data processing. Then, we need to implement Naive Bayes Classifier.

OUTPUT

1. Accuracy of Training set = 91.45 %
2. Accuracy of Testing set = 79.26%
3. Classification report
<img width="418" alt="image" src="https://github.com/shreya-malraju/Naive_Bayes_from_scratch_Text_Classification/assets/132793649/3a63e349-cb98-446c-b28f-182bd97578e2">
