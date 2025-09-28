# T-Test
T-test is a method to fit a line through all the data of 2 parameter using certain optimizing algorithm (usually least squared, mean squared, coefficient of determination or $R^2$ etc). T-test follow the same algorithm as linear regression  
  
$$Y = mean_1 + mean_2$$  
  
where $mean_1$ and $mean_2$ represents the parameter for Y equation. Using the same approach as linear regression, 
it will result in a line that will fit through all the data. By following the F-statistic value from linear regression of form  
  
$$F_observed = ((SS(mean) - SS(fit)) / (p_fit - p_mean)) / (SS(mean) / (n - p_mean))$$  
$$or$$  
$$F_observed = ((Var(mean) - Var(fit)) / (p_fit - p_mean)) / (Var(mean) / (n - p_mean))$$  
  
with Var(mean) represents the variation of only the predicted parameter and Var(fit) represents the variation of 
the line of Y to the actual data which the general equation for Var(X) follow as below  
  
$$Var(X) = SS(X) / n(X)$$  
  
with n(X) is the number of sample and SS(X) is the Sum of least Squared(X) of that $\textbf{particular category}$.  

# Motivation
Given a dataset (categorical) of $\textbf{n parameter}$, how do you fit a line through all the data such that the distance from each data from the dataset is the minimum compared to other line configuration?

# Limitation
Best work on categorical dataset. 

# Algorithm
1. (Do later)

# Example
(Do later)