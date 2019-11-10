---
title: "Data Science and Machine Learning Review"
date: 2019-10-30T19:38:53-04:00
draft: False
tags:
- anthology 
- review
- comprehensive

---

As I prepare for my final Machine Learning interview with Lyft, I look back on my Data Science career and projects. I also want to give a brief overview of the subjects that are useful for machine learning and data science.

Data science type positions:
1. Basic statistics
2. Basic probability
3. Linear Regression
4. Normal equation


It is difficult to draw the line precisely between machine learning and data science. But generally, I would view machine learning as more on the computational side, while data science is more statistical. 

We can perform linear regression using a neural network and gradient descent. Or we can also use the normal equation! (Which is beautiful, framing optimization as a projection, which has the property that it is also the minimizer)

Machine learning:
Feed dict: Tensorflow and the computational graph!
PyTorch Refresher:  Pytorch and the eager executor
Sci-Kit Learn refresher: fit and fit transform!

1. Algorithms
   1. Unsupervised
      1. Frameworks such as Expectiation Maximization
   2. Supervised
2.  Time Series Prediction
    1.  There are several flavours:
        1.  Imputing missing data: 
            1.  we can use ARIMA, other approaches
        2.  Fitting a regression line
            1.  The regression line gives us a free estimate of the conditional mean, everywhere along the domain!
    2.  Note that this can be cast in several ways. For instance, an LSTM or RNN can be used to run inference on unseen data.
   
3.  Some more niche areas of ML, including one that surprisingly Ben mentioned: multi-armed bandits, and some type of graphical model explored in 412...
4.  Online machine learning etc.
5.  Bias variance decomposition
6.  Kalman filters and Online Learning
7.  Thomson Sampling, Gibbs distribution

Nice questions that I was asked:
8.  Which is more important to you– model accuracy, or model performance?
9.  It depends on what you mean by performance! F1 score, run time etc.
10. note that if we say predictive power/predictive analytics is key, then the actual key points of a model deal with something more akin to predictive power, or rates.
11. Can I simply explain the Shen paper?

**Design of experiments**
paired t-tests, etc.
factorial design
randomized block tests; block design, factors

connections between parameter estimation and machine learning; when you are doing certain types of cross entropy, really we are just maximizing log likelihood

Ben brought this up a few times during the interview: how would you 

a) assess the impact of your campaign?
b) design an algorithm to move the needle on consumer behaviour?

Most of them are looking at time series prediction, forecasting demand etc.

things I never did:
connecting partition of a vector space into orthogonal complements, with its usefulness. Sure, we can show that, but why is it a useful prperty? Probably because you can always express any thing, as a combination of its component in the orthogonal complement, and the original vector ==> this is EXACTLY what we are doing in a projection separating out the projection into its 


My predictions for the machine learning interview:
1. 