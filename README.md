# Freeze-Thaw Bayesian Optimization

By Kevin Swersky, Jasper Snoek, Ryan Prescott Adams

In this paper we develop a dynamic form of Bayesian optimization for machine learning models with the goal of rapidly finding good hyperparameter settings. Our method uses the partial information gained during the training of a machine learning model in order to decide whether to pause training and start a new model, or resume the training of a previously-considered model. We specifically tailor our method to machine learning problems by developing a novel positive-definite covariance kernel to capture a variety of training curves. Furthermore, we develop a Gaussian process prior that scales gracefully with additional temporal observations. Finally, we provide an information-theoretic framework to automate the decision process. Experiments on several common machine learning models show that our approach is extremely effective in practice.

Copyright by Kevin Swersky, Jasper Snoek, Ryan Prescott Adams, 2014
Copyright by the Dendi Suhubdy, 2018
