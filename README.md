# Predicting-Corporate-Defaults-Using-Machine-Learning

Trying to predict whether a company will default or not in upcoming year using machine learning model. Ideally, 
there should be multiple in depth fundamental and statistical ways to predict this. This is more of a gneral diagnostic approach where after flagging by this algorithm, 
a manual in depth research can be carried by an analyst. Moreover, we can rank the probabilities of default for each firm, and then use it for some another algorithm of strategy devlopment of credit research.

This can work as a flag to analyze credit defaults, and have an early flagging system for corporate defaults.

We collected multiple variables on the performance of all the firms in the COMPUSTAT univers, use it's returns from the CSRP data.
Various fundamental variables (ratios), market variables, distance to default parameters and macroeconomic variables are taken as features. Multiple models are run, checking the ffectiveness of each variable for each model.
The models include 
Logistic Regression 
Ridge and LASSO  Regression
K Nearest Neighbours 
Random Forest and Survival Random Forest 
Gradient Boosted Trees and Artificial Neural Networks.  
