# Linear Regression
Linear Regression is a method to fit a line through all the data using certain optimizing algorithm (usually 
least squared, mean squared, coefficient of determination or $R^2$ etc). Linear regression will follow below formula
  
$$Y = \beta_0 + \beta_1x_1 + \beta_2x_2 + ...$$  
  
with $\beta_x$ represents the coefficient value and $x_i$ represents the parameter that will be used
for predicting the constrained parameter (Y). In practice, the value of each $\beta$ will be started from small value 
near 0 and when calculating the optimizing algorithm, each $\beta$ will be customized such that the final changed
equation of Y will cause the optimizing algorithm to be as small as possible (which represents the minimum difference
between the actual value and the predicted value).  
The optimizing algorithm used is usually $R^2$ or Cofficient of Determination, which quantifies the
relationship in the data and follows below equation  
  
$$R^2 = (Var(mean) - Var(fit)) / Var(mean)$$  
  
with Var(mean) represents the variation of only the predicted parameter and Var(fit) represents the variation of 
the line of Y to the actual data which the general equation for Var(X) follow as below  
  
$$Var(X) = SS(X) / n(X)$$  
  
with n(X) is the number of sample and SS(X) is the Sum of least Squared(X) of that particular sample.  
  
Meanwhile, for a testing how reliable that relationship is, we'll need to calculate the $p-value$, which will be used
for hypothesis testing. $p-value$ or probability value is a value which represents how likely a given hypothesis null 
(hypothesis that the dataset is representing the relationship accurately) if given a condition of a sample that 
don't comply to the hypothesis null.  
Usually, p-value for linear regression will be using F-distribution as it is
the most common and applicable distribution for multiple parameter predicting a certain parameter. p-value will be 
calculated by calculating F-statistic first, which follows

$$F_observed = ((SS(mean) - SS(fit)) / (p_fit - p_mean)) / (SS(mean) / (n - p_mean))$$  
$$or$$  
$$F_observed = ((Var(mean) - Var(fit)) / (p_fit - p_mean)) / (Var(mean) / (n - p_mean))$$  
  
where $p_fit$ is the number of parameter used for prediction (k), n is the number of population, and $p_mean$ is the number 
of predicted parameter.  
  
Given a value for F and a chosen threshold of $\alpha$, $\alpha$ is then converted into F-statistic value ($F_critical$) and
compared with the $F_observed$ where 
1. if $F_observed \ge F_critical$, $H_0$ is rejected,
2. else $F_observed < F_critical$, we cannot reject $H_0$


# Motivation
Given a dataset (numerical or categorical encoded into integer), how do you fit a line through all the data such
that the distance from each data from the dataset is the minimum compared to other line configuration?

# Limitation
Best work on numerical dataset. Categorical dataset need encoding into integer and rounding of the predicted value 
to determine what category does the data belong. Categorical dataset will use t-test (for two unconstrained parameter) or
ANOVA (for > 2 unconstrained parameter)  

# Algorithm
1. (do later)

# Example
(Do later)