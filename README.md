# Deep-learning

#Dataset

We have chosen the penguins dataset from the seaborn package that includes the features 'species', 'island', 'bill length mm', 'bill depth mm', 'flipper length mm', 'body mass g', 'sex'

#Feature Selection

For Feature selection we have chosen to focus on the bill length, depth and mass for penguins and see if those features can be used to identify the sex of the penguins.

#Feature Engineering 

The only feature engineering that has been done is to change the sex from Female to 1 and Male to 0. Then we have scaled the bill length, depth and body mass so the values are of the same scale.

#Standard ML Preprocessing 

In preprocessing we have looked for nan and have removed them since there were not that many and the dataset can still be used without the rows with missing values

#Evaluating the Final Model on the Test Data

We can se that the model has a accuracy on 0,85 on the test data and given the small sample size and few features that the result is acceptable 
