The code file detects spam emails from given dataset by applying naive Baye's algorithm. Initilally, we do feature engineering using the Count Vectorizer method to create feature vectors for each message in the dataset.
For each word in our vocabulary, it has the value 1 if the word is present in the message and 0 if it is not.

Then, we apply the naive bayes algorithm to find the probabilities for each feature and then predict the output (spam or not spam).

We see that Naive bayes has limitations especially when any input feature has 0 frequency. Thus, we apply smoothing to overcome this situation.

The code finally displays the sum of log of probabilities for each output class ( not spam and  spam i.e. 0 and 1).

Please note that the accuracy of predictions has not been performed in the code.
