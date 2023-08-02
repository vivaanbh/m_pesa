# m_pesa
Analyzing the determinants of mobile money adoption using data from a survey of 2,282 households in Kenya on M-pesa, a successful mobile money application. 

In low-income countries, mobile money is a substitute for banking access. In fact, individuals
do not need a bank account to perform financial transactions (send and receive money) via
their mobile service. One of its biggest advantages is that it can reach the most remote and
vulnerable populations.

In this project, both supervised (logistic, DT, RF) and unsupervised (KNN) techniques of machine learning are used to classify observations.

Contents:
- Data
- Descriptive stats on key variables and outcome variable, mpesa_user.
- Supervised Learning classifiers (Logit, DT, RF). Using 80-20 train-test split. Compare performace using AUC criteria.
- Top 3 predictors based on best classifier.
- Unsupervised Learning method, KNN. Perform a grid search for optimal value of K.
- Choosing the best model and recommendation.
