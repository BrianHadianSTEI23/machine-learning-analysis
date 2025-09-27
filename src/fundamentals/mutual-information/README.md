# Mutual Information
Mutual Information is a numeric value that gives us a sense of how closely related two variables are. Mutual 
Information is based on entropy in the sense that when entropy gives the surprise (change) we see in one variable 
that is used for outcome, mutual information gives the suprise (change) in one variable that is related to the surprise (change) in another. Mutual information follow formula below
$$ MI = \sigma\sigma(p(x, y))log(p(x, y) / (p(x) * p(y))) $$
In a brief sense, if given one support parameter and one target parameter which both have a correlation (inverse or not), 
it will converge into 0.5. And when it is not, it will diverge from it as far as possible.

# Motivation
Given a dataset with > 2 parameter, how do you determine which parameters have significant effect on the target column?

# Limitation
best work for categorization task. May work with numerical data, but needs conversion into histogram (categorize it
into categorical data)

# Types of Algorithm name (If exist)

## Algorithm

# Example
