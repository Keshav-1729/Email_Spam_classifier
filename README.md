# Email Spam Classifier

Used a dataset consisting of spam and ham emails in order to train 3 various classifier namely Gaussian naive bayes classifier, Multinomial Naive Bayes and Logistic Regression and comparing the scores of the classifiers to select the best one. Used CountVectorizer to convert the text data to numerical data in the form of a matrix.

Used pipeline API to avoid separate transform and predicting the outcome.
## Reason for low performance of GaussianNB:
GaussianNB is used for continuous data since it uses the Gaussian distributions to make the prediction and MultinomialNB is used with the Discrete data.
