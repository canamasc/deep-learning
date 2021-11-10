# deep-learning
Charity Funding Predictor

The purpose of this analysis is to examine the effectiveness of using neural networks and deep learning models to accurately predict the success of various applicants that have been funded by Alphabet Soup foundation (classification).

The data is first cleaned and separated to exclude target variables. Irrelevant variables are dropped and the data is scaled using StandardScaler. Categorical data is dealt with using Pandas' get_dummies.

We experimented with the neural network, varying the activation functions, number of neurons, and number of hidden layers, as well as the number of epochs used in training. 

The goal of 75% accuracy was not achieved - best performance was 73.16%, which is still decent. 

