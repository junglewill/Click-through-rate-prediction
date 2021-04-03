# Click-through-rate-prediction

This is a mini Kaggle Competition held in the course of Machine Learning for Financail Engineering & Operation Research at Columbia University. Our solution won the 4th place out of 47 teams. The dataset was slightly modified from the click-through rate prediction contest by <a href='https://www.kaggle.com/c/avazu-ctr-prediction'>Avazu</a>.

### The process we took in this project:
  1. EDA and run simple models on the top 20,000 rows
  2. Feature engineering and data preprocessing
  3. Bayesian optimization for hyperparameter tuning using bootstrapped sample in 12 models, using CatBoost, XGBoost, and LightGBM.
  4. Bagging ensemble using weighted average

* we also try out some of the following methods, but it didn't show as good results:
  1. Experimented with other forms of encoding the categorical predictors, such as K-fold
target encoding and sklearn’s FeatureHasher.
  2. Deep Learning models: MLP, existing neural networks libraries (deepctr and deeptables)

For more information please check our <a href='https://github.com/junglewill/Click-through-rate-prediction/blob/master/Report_and_approach.pdf'>final report</a>. Feel free to contact me if you have any questions.

