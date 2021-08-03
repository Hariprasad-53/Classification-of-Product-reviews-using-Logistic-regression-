# Classification-of-Product-reviews-using-Logistic-regression-

The focus of this project will be to classify reviews from the following three websites: 1) imdb.com, 2) amazon.com and 3) yelp.com using the logistic regression classifer.

The dataset containins 3000 sentences and was collected from the UC San diego ML repository - https://archive.ics.uci.edu/ml/datasets/Sentiment+Labelled+Sentences

The data set already contains 500 positive and 500 negative reviews/ sentences from each of the aforementioned websites.

Negative review has been labeled as 0 and a Positive review has been labeled as 1 in the data set.

The following steps are used to construct a logistic regression model and hence to train the model:

a) Reading the dataset and assigning the reviews and labels to different variables

b) Preprocessing the data, which includes: removing the punctuations, numbers, stop words, converting the words to lower cases and finally converting the sentences to vectors, using bag-of-words representation

c) Declaring variables to hold the training and test data, labels

d) Finally fitting the logistic regression model by using SGDClassifier of the library sklearn

e) Finding those words which have the most +ve and -ve influence in the dataset

f) Analysis of the margin, which includes finding, plotting which points lie above the margin and also plotting the decrease in error rate when the margin increases
