# agnews_text_classification

## Description
The overall objective of the project was to create different NPL algorithms which can classify text into the categories Science, Sports, World, and Business. Labeled data split into train and test data was provided, allowing us to right away get started with experimenting with different models and hyperparameters. By comparing the performance of the different models, we want to give a recommendation on which model should be used in order to make the most accurate predictions possible.

## Model Overview

### General Approach

In a first step, we needed to decide which models we would like to experiment with. After making some research, we decided to test (1) Multinomial Naive Bayes 
Models, (2) Stochastic Gradient Descent Models, and (3) Multiclass models. Multiclass models have the advantage that they integrate the prediction of all different classes into one model, while multinomial naive bayes models and stochastic gradient decent models are separately build for all prediction classes.

### Multinomial Naive Bayes Model

Multinomial Naïve Bayes Models take on a probabilistic approach for constructing the data classification models by dealing with probability as the ‘likelihood’ that data belongs to a specific class. Researching best practices when creating Multinomial Naive Bayes Models, we found two main approaches to dealing with ngrams. The first approach is to combine unigrams with bigrams, trigrams, etc. when searching for the best hyperparameters. The second approach is to separate unigrams from bigrams, trigrams, etc. thus only allowing the model to learn from either or. 

### Stochastic Descent Model

Stochastic Gradient Descent is a simple but efficient approach to fit classifiers under convex loss functions.

### Multiclass Model

Multiclass models strength lies in integrating the prediction of all different classes into one model which significantly increases the value of the model. 

## Additional Information

### Learning Curves

Learning Curves can be used to compare different algorithms, and to determine the amount of data which should be used for training.

### Precision-Recall Curves

The Precision-Recall curves summarize the trade-off between the true positive rate and the positive predictive value for a predictive model using different probability thresholds.
