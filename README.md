# Tree-Models

We give an overview on the theory of different tree models (Decision Trees, Bagging, Random Forest, Gradient Boosting) and their application in R using an example dataset.
Further we present a suitable search for the best hyperparameters.
Different tree models are then being compared with a linear model.
Finally we write our own algorithm creating a mixd model that uses Random Forest logic on a backward selected linear model.
The models are being compared by RMSE, MAE and run time.
The tuned Random Forest model and the tuned Gradient Boosting model showed the best restults considering the made error only. The also took the longest to run by far which was, however, not a problem with our dataset. But considering the time needed to tune the hyperparameters they are a bit more time consuming for their programmer.
