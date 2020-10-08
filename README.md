# LendingClub_default_prediction
This is a project that I and a friend worked on during our data science bootcamp. The goal is to predict if a given loan from the credit platform LendingClub will default or not. 

## Methods
Random Search was used on the classification algorithms of random forest, xgboost, logarithmic regression and support vector machine. The search was conducted with the goal to minimize the recall, because we only want to accept creditors who we are sure of that they will not default. 

Interestingly, the log regression is currently the model that led to the minimal rate of false negatives.

## Future work
We want to investigate what kinds of loans (they have different risk premiums) are being accepted and rejected by a given model and if using this model would actually improve investment returns.
