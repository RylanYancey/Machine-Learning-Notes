# Chapter 1 - Introduction
## What is Machine Learning?
- A subfield of computer science that is concerned with building algorithms which rely on a collection of examples to inform behavior. 
### Supervised Learning
The data is a set of labeled examples, denoted $\\{(x_i, y_i)\\}^{N}\_{i=1}$. This can be read as: A set of labeled examples where $x$ is the input and $y$ is the desired output. Each element $x$ is a feature vector in $N$. A feature vector is an input without multiple "attributes". $i=1$ indicates that each $x$ must have at least one element. 

In Supervised learning, it is important to note that the data is *known*, and has been labeled with a *correct* answer. A given input correlates with a desired output.

## Support Vector Machine
Used in the book to demonstrate Supervised Learning. A Type of machine learning that requires the positive label has the numeric value of +1, and the negative label has the value of -1. 

The dimensionality of an SVM is equual to the number of inputs. If you have 20,000 inputs, the model is 20,000 dimensional. The model will create a 19,999-dimensional line (a hyperplane) that separates positive and negative examples. This hyperplane is called the *decision boundary*

The equation of this line is given by only two parameters: a feature vector $w$, and a base $b$: $$wx - b = 0$$ 
Where the expression $wx$ means: $$w^{(1)}x^{(1)} + w^{(2)}x^{(2)} + ... + w^{(D)}x^{(D)}$$
The goal of the learning algorithm is to leverage the dataset and find the optimal values $w*$ and $b*$ for parameters $w$ and $b$. Once the learning algorithm identifies these optimal values, the model $f(x)$ is defined as $f(x) = sign(w\*x - b*)$. Where * is "star". 
