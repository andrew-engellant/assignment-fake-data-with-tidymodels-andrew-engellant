# Fake Data Analysis with Tidymdoels

This assignment asks you continue to work with the synthetic data
set from the previous assignment. 

## Tasks

In the previous analysis, you built a linear regression
model and reported the results. Then you used a hold-out
sample to estimate the error of your regression model. Finally, you fit
a tree model using `rpart` and estimated its accuracy. 

In this assignment, I ask you to do the same tasks, but using tidymodels
syntax. Your linear regression should be defined with a call to `linear_reg` and the
tree should be set with `decision_tree` (or `random_forest` if you'd like to play with that). 
Both will use `set_engine` and feel free to use `lm` and `rpart` respectively. 

Use `initial_split` to do your training and assessment splits. Use a line, like
this one from the lecture, to measure the accuracy: 
```
metrics(d.test,truth=air_quality_index,estimate=pred_lm)
```

As always, take a bit of time to interpret your results. The linear regression
model commentary can be pulled directly from the previous assignment. Make
sure your HTML is well formatted and that your report reads like an actual
document rather than a screen dump. 

If you use an LLM for this assignment, start a fresh chat as you begin work and include a link to your chat in your submission. 

## Feedback 

Very nice work on this and kudos for using some of the recipe functionality. 
