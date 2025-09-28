# Multiple Regression
Multiple Regression is a method to fit a dimension (n - 1) through all the data of n parameter using certain optimizing algorithm (usually least squared, mean squared, coefficient of determination or $R^2$ etc). Multiple regression will follow below formula  
  
$$Y = \beta_0 + \beta_1x_1 + \beta_2x_2 + ...$$  
  
Using the same approach as linear regression, it will result in a dimension (n - 1) that will fit through all the data,
assuming the data can be plotted in n dimension.  
By following the F-statistic value from linear regression of form  
  
$$F_observed = ((Var(mean) - Var(fit)) / (p_fit - p_mean)) / (Var(mean) / (n - p_mean))$$  
  
multiple regression can be compared to the linear regression by changing the value of every element that came from 
$mean$ dataset to be converted with the corresponding element in the same equation from linear regression. Because $F_observed$ 
has linear correalation with $R^2$, the result that came from $F_observed$ will represent the $R^2$ and if $R^2$ is big enough,
it implies the significance of the additional parameter in the multiple regression such that it is $\textbf{recommended to 
consider additional parameter into the model}$.

# Motivation
Given a dataset (numerical or categorical encoded into integer) of $\textbf{n parameter}$, how do you fit a dimension n - 1 through all the data such that the distance from each data from the dataset is the minimum compared to other dimension n - 1 configuration?

# Limitation
Best work on numerical dataset. Categorical dataset need encoding into integer and rounding of the predicted value 
to determine what category does the data belong.  

# Algorithm
1. (Do later)

# Example
(Do later)