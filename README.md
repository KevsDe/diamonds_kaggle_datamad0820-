![img](https://user-images.githubusercontent.com/66921012/95157694-1abec500-079a-11eb-9551-2e1994f986d9.jpg)

# Ironhack datamad0820 Kaggle competition, the goal of this competition is to predict the price of diamonds based on their characteristics.

Information sources:
* [Kaggle link](https://www.kaggle.com/c/diamonds-datamad0820)

For this project I used:
Libraries:
* Pandas
* Numpy
* Scikit-learn
* Matplotlib
* Seaborn
* Keras
* H2o

## The objective of this exercise are:
* Get involved into a real Kaggle competition between all the classmates.
* Perform an analysis and cleaning of the data, testing multiple models, libraries, features, etc, in order to find predictions as accurate as possible. 
* Practice all the machine learning knowledge provided in class. 
* Have fun with the classmates. 
## Metrics:
* Mean-squared-error
* R2-score
* Negative-mean-squared-error
* Root-mean-square-error
## Better results on Kaggle ́s public leaderboard(Root-Mean-Squared-Error):
* H2o AutoML: 515.89666
* ExtraTreesRegressor: 529.66702
* RandomForestRegressor: 584.23490
## Conclusions:
* After testing with multiple feature combinations, removed the outliers, applied a bunch of models and even some neuronal nets, my conclusion is all the information contained in the data set is value data, removing the outliers your estimations become worst, assemble a neuronal net is complicated and h2o AutoML proved to be the chosen one because it performs hyperparameter search over a variety of H2O algorithms in order to deliver the best model.