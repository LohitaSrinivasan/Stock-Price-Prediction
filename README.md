# Stock-Price-Prediction

# Introduction
1. Objective
2. Why Neural Networks
3. Hyperparameters tuning
4. Challenges
5. Learnings


We are provided with monthly stock price returns for 58 years, number of stocks is 18719 and we are provided with a dataset of these having 64 features to be modelled with. We are predicting the stock returns for 42 years, creating portfolio to buy top 10% and sell bottom 10% and determining portfolio returns for 42 years. Sharpe ratio is calculated for 42x12 months. Annualized sharpe ratio is then calculated.

# Objective
1.The objective is to explore the hyperparameters of deep neural networks to understand the intuition behind the final architecture 2.End goal of the tuning is to have the sharpe ratio more than 5.2 and the R-square ratio to be around 0 using different hyperparameters

# Why Neural networks
Non-linear relationship

Huge data availability

Fit highly complex data using large number of parameters

Infer relationships well on unseen data

Proven very effective in many applications

# Hyperparameters considered
Number of Layers Number of Neurons Optimizer Activation function Batch Size Learning rate Patience for early stopping

# Hyperparameters analysis
#1 (comment) #2 (comment)

# Challenges encountered
Gradient Vanishing problem Gradient Exploding problem Running time Memory error due to large datasets

# Overall Learnings
It is very important to use our intuition while training the deep neural networks as it is not practical to use all the possible combinations There are new combinations that have been tried Kernel Initializer Encountered Vanishing Gradient descent Encountered Exploding Gradient descent Importance of Dropout Alternate activation functions The Modelling exercise is all about trying different parameters and understanding the directions ââWe learned a lot about what not to do!!â- Deep Learning thoughts

# Outcome
The project focused on hyperparameters tuning of a base deep neural network architecture. Our goal was to improve the Sharpe ratio and Prediction accuracy that the existing architecture could best achieve. In order to perform this, different combinations of neurons and corresponding layers, optimizers, learning rate, epochs, batch-size. We achieved ~7% increase in sharpe ratio and 97% increase in Prediction accuracy for excess market returns.
