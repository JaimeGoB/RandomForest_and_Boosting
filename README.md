# RandomForest_and_Boosting

## (a) Fit a tree to the data. i) Summarize the results. Unless the number of terminal nodes is large, ii)display the tree graphically and explicitly iii)describe the regions corresponding to the terminal nodes that provide a partition of the predictor space (i.e., provide expressions for the regions R1,...,RJ). iiii)Report its MSE.

<p float="left">
  <img src="https://github.com/JaimeGoB/RandomForest_and_Boosting/blob/main/data/decision_tree.png">
</p>

## iii) Describe Regions
## iiii) Report MSE - Decision Tree 

0.1342


## (b) i) Use LOOCV to determine whether pruning is helpful and determine the optimal size for the pruned tree. ii)Compare the pruned and un-pruned trees. iii) Report MSE for the pruned tree. iiii) Which predictors seem to be the most important?

<p float="left">
  <img src="https://github.com/JaimeGoB/RandomForest_and_Boosting/blob/main/data/pruned_decision_tree.png">
</p>

## iii) Report MSE for the pruned tree.

0.2322


## (c) i) Use a bagging approach to analyze the data with B = 1000. 

## ii) Compute the MSE.
0.0219
 
##iii) Which predictors seem to be the most important?

<p float="left">
  <img src="https://github.com/JaimeGoB/RandomForest_and_Boosting/blob/main/data/bagging.png">
</p>

## (d) Repeat (c) with a random forest approach with B = 1000 and m = p/3
## i) Use random forest approach with B = 1000 and m = p/3

## ii) Compute the MSE

0.0303
 
## iii) Which predictors seem to be the most important?
<p float="left">
  <img src="https://github.com/JaimeGoB/RandomForest_and_Boosting/blob/main/data/random_forest.png">
</p>


## (e) Repeat (c) with a boosting approach with B = 1000, d = 1, and lambda = 0.01
## i) Use boosting approach with B = 1000, d = 1, and lambda = 0.01
## ii) Compute the MSE

0.1229

## iii) Which predictors seem to be the most important?
<p float="left">
  <img src="https://github.com/JaimeGoB/RandomForest_and_Boosting/blob/main/data/boosting.png">
</p>

#### (f) Compare the results from the various methods. Which method would you recommend?
<p float="left">
  <img src="https://github.com/JaimeGoB/RandomForest_and_Boosting/blob/main/data/results.png">
</p>


