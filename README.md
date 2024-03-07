# machine-learning-basic
Machine learning and statistics for classification and predication. Simple project for personal training / learning purposes. 


## Problem 1. Can the model be written as a linear regression model?
We will only consider the 3 methods:

(i) as they are;

(ii) when a single parameter is held fixed; 

(iii) after a suitable transformation (i.e., use the same transformation on both y and f(x))?

### a
$$y = \frac{\beta_0}{1 + \beta_1x} + \beta_2\sqrt{x_1} + \epsilon$$

Is nonlinear due to the presence of the term $\frac{\beta_0}{1 + \beta_1x}$ and $\sqrt{x_1}$.

A linear regression model is typically of the form:

$$y = \beta_0 + \beta_1x_1 + \beta_2x_2 + ... + \beta_nx_n + \epsilon$$
where $y$ is the dependent variable, $x_1, x_2, ..., x_n$ are the independent variables, $\beta_0, \beta_1, ..., \beta_n$ 
are the parameters of the model, and $\epsilon$ is the error term. 

Even if we try a simple transform or holding a parameter constant, the model will still be nonlinear. 

### b
