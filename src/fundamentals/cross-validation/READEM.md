# Cross Validation
Cross validation is a method to check what algorithm is the best for the current data by applying it into the data
and then testing the model by using the test data for determining if the model got it right. For each algorithm, it
is counted for how many sample that got right and wrong. Those algorithm which has the most rights will be chosen for 
further use in the model

# Types of Cross validation
1. N-Fold cross validation
> Data is split into N blocks and for N times, N - 1 blocks is chosen as training data and the leftout block will be chosen as test data.
Every iteration, the leftout block will be chosen again such that it is not the block that has been used as test data.
2. Leave one out validation
> Every sample (N) - 1 is run through the algorithm and one is chosen as test datum. This will be done N times with every iteration, 
the leftout datum will be chosen again such that it is not the datum that has been used as test datum.