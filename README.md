# Song-Popularity-Prediction-with-nonlinear-hyperparameter-optimization-
- Our experiments use several optimization techniques to perform hyperparameter optimization on several machine learning models. The experimental environment is jupyterLab.
- The required dependencies are as follows:
  - pandas, numpy, seaborn, sklearn, scikit-optimize, textblob, lightgbm.

- First we import the Spotify song dataset, preprocess the data and perform feature engineering.
- Next, we perform hyperparameter optimization using Bayesian optimization, grid search, and random search for LightGBM, kNN, SVM, random forest, and AdaBoost, respectively. The chosen hyperparameter optimization method library is skopt and the models are from sklearn. The ROC curves are plotted using the method in matplotlib.
- Just run the code in sequence.