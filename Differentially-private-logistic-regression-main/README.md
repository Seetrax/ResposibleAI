# Differentially-private-logistic-regression

In this repository, I have implmented a differentially private logistic regression.
Differential privacy can be attained by three methods :
        perturbing the input
        adding noise to the error gradient in the model during the learning process
        perturbing the output.

In this repo, I have altered the model of a logistic regressor, so as to add a 
noise vector sampled from a gamma distribution to the error 
gradient so that only the new noisy gradient will be subtracted from weights
each epoch.
