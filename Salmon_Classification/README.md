The given code initially calculates the mean and covariance from given input data ("Salmon_Dataset.csv") for two input classes - Alaskan and Canadian.

It then uses test data ( Currently hardcoded in the code) and then predicts the output class for 10 sample values.
The prediction is done by calculating the probability that the input lies in a class ( Canadian or Gaussian).
For this, the mean and covariance calculated for each class from the training data is used and the corresponding gsussian distribution is calculated.
Depending on whether the probability is higher for Alaskan or Canadian, the prediction is made.

The calculations for mean and covariance matrix have been done through my own logic instead of np.mean() or np.cov() functions.
