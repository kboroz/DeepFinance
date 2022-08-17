# DeepFinance

This GitHub-repository includes a couple of IPython-Notebooks which where executed to fullfil the requirements in the OpenCampus "Deep Learning" course  held in the summer term 2022.

Starting point is the "black_scholes_learning_prices.ipynb" file where we trained a neural network to learn and predict prices.

In a similar fashion the "ModelParameterVasicek.ipynb" files shows how to use NN to train, learn and predict the parameters of an underlying stochastic process - here i.e. the so-called Vasicek-model.

The "black_scholes_learning_iv.ipynb" file is the major part of the project. It includes some routines to calibrate model and/or market parameters of the implied volatility. In addition with the "aapl_190722.csv" CSV-file, which includes option prices and parameters of the Apple stock from July-19, we adapted the procedure to real data.

The "DeepHedging.ipynb" is just an Add-On which should and will be continued in the future term to show how to train a neural network for hedging purposes.
