# titanic_kaggle
A model classifying whether a person would survive on Titanic <br />
Data: https://www.kaggle.com/c/titanic <br />
The main model is catboost. <br />
Categorial features were encoded with one-hot. To find the best features set I used greedy deletion algorithm. <br />
Also I used 2 grid searches - <code> catboost grid_search</code> and grid search written by me.<br />
Validation result - 0.909(ROC_AUC)
