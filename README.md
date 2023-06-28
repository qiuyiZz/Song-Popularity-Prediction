# Song-Popularity-Prediction-with-nonlinear-hyperparameter-optimization
The project uses several machine learning models, including LightGBM, kNN, SVM, random forest, and AdaBoost, to predict song popularity and compare the performance of grid search, random search, and Bayesian optimization performing hyperparameter optimization on different models to finally obtain a model with the best prediction performance.

I performed data processing and feature engineering on the song feature dataset with pandas, numpy, seaborn, sklearn and textblob and performed hyperparameter optimization using skopt library. I build a performance evaluation benchmark includes accuracy, precision, recall, F1 score and AUC to evaluate the model performance. The objective is to compare the performance of different hyperparameter optimization techniques on different machine learning models and finally determine the best hyperparameters combination for model performance. By building predictive models with good accuracy, we can improve the recommendation accuracy of digital music platforms and enhance user experience. Through this experiment, I obtained the model with the best overall performance and efficiency, i.e., the Bayesian optimized LightGBM model.

Our experiments use several optimization techniques to perform hyperparameter optimization on several machine learning models. The experimental environment is jupyterLab.

- The required dependencies are as follows:
  - pandas, numpy, seaborn, sklearn, scikit-optimize, textblob, lightgbm.

- First we import the Spotify song dataset, preprocess the data and perform feature engineering.
- Next, we perform hyperparameter optimization using Bayesian optimization, grid search, and random search for LightGBM, kNN, SVM, random forest, and AdaBoost, respectively. The chosen hyperparameter optimization method library is skopt and the models are from sklearn. The ROC curves are plotted using the method in matplotlib.
- Then run the code in sequence.
