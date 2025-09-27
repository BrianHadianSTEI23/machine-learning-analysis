# Specifity and Sensitivity
Sensitivity is a metric calculated from confusion matrix which represents how good the algorithm is predicting 
true positives of a certain value in the predicted column. It follows formula below  
  
$$Sensitivity = true positives of that certain value / (false positives of that certain value)$$  
  
Specifity is a metric calculated from confusion matrix which represents how good the algorithm is predicting the 
true positives OTHER THAN certain value which is checked at that current iteration in the predicted column. It follows formula below  
  
$$Specifity = true negatives of OTHER THAN certain value / (false negatives of OTHER THAN certain value)$$  
  
These two are calculated for each distinct values in the predicted column and the final value of specifity and sensitivity
is compared with the calculation from other algorithm and you choose the method that resembles the accuracy of certain values that
you want.

# Motivation
Given a confusion matrix of a task, how do you determine which algorithm is the best

# Limitation
Only works for categorization task

# Algorithm
1. (do later)

# Example
(Do later)
