# Random Variable (it's mostly probability stuff)
Random variables are written as capital italic letters, like: _X_. 

## Discrete vs Continuous
Discrete random variables are countable, such as red, yellow, blue, or 1, 2, 3. 
Continuous random variables are not countable, such as 0.0, 9.4, 15.3, etc.
(effectively, whole numbers vs floats)

## Probability Distribution
...of a discrete random variable is described by a list of probabilities associated with each of its possible values. 
This is called a `probability mass function`. For example, Pr(_X_ = red) = 0.3, Pr(_X_ = yellow) = 0.45, etc. Each probability must be greater than 0, and the sum of all probabilities is 1. 

## Continuous Random Variable
An Infinite number of possibilities. Created a probability density function, where the _area_ under the curve of the function is equal to 1. See page 16 for more details.

## the Mean \ average.
u = mean

## The Expectation of _X_
Expectation\[_X_] def= SIGMA \[distr\[i] * Pr(X = distr\[i])]\
This can be read as:\
```
The Expected Value of X is equal to the sum of all (values * that values probability). 
```
The Expectation is denoted with a weird E. (like a gothic E)

## Standard Deviation
stdev def= sqrt(E\[(_X_ - u)^2]
```
The standard deviation is equal to the square root of the Expected value times (the random variable X - the mean) squared. 
```

## Variance
denoted as osquared or var(_X_)\
var(_X_) = E\[(_X_ - u) ^2]
It's standard deviation, but without the square root. 

## Expectation of _X_, for a continuous random variable. 
See page 16
