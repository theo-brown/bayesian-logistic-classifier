# Bayesian Logistic Classification
## Abstract
Maximum likelihood estimation using gradient ascent optimisation is presented as a means of training a linear classifier. 
The linear classifier is trained on a test data set, and shown to perform poorly. 
A set of non-linear basis functions are introduced, which can be applied to the input data to enable the logistic regression model to fit to non-linear data sets. 
The classifier using basis functions is shown to perform well on the data set, after manual tuning of the basis function parameters.
To extend the logistic classifier, two methods of Bayesian Classification are presented, based on the Maximum A Posteriori (MAP) estimate of the model weights and the Laplace approximation of the posterior distribution of the weights.
The performance of the Laplace classifier is shown to be superior to the MAP and Maximum Likelihood (ML) classifiers, exhibiting reduced overfitting, a closer fit to the data, and a higher correct prediction rate.
Optimisation of the hyperparameters of the model is achieved using the Laplace approximation of the model evidence, demonstrating a principled approach to hyperparameter setting.

## Reports
The results are compiled into two reports:
1. [ML Logistic Classification](out/ML_Logistic_Classification.pdf)
2. [Bayesian Logistic Classification](out/Bayesian_Logistic_Classification.pdf)

## Marks
The reports were submitted as coursework for 3F8: Inference, a module taken as part of Part IIA (third year) of the Engineering Tripos at the University of Cambridge.

*ML Logistic Classification* was graded as a First (100%).

*Bayesian Logistic Classification* is awaiting marking.
