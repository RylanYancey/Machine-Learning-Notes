# One-Stop Notation Shop

The following comes from:
Pages 10 - 20

One place for all the notation AND definitions found in this book.

## Set Notation

Set: "unordered collection of unique elements"
```
set = { 50, 1.4, 9903, 332 }
```
Sets are denoted as { e1, ..., en } with curly brackets. 

Set Belonging is denoted with an Epsilon:\
![Epsilon for Set Example](https://user-images.githubusercontent.com/76256852/176782950-50c5958b-bafc-4ffd-b6fe-a48330be3155.png)

The special set R denotes a set of all numbers -inf to +inf.

[a, b] set from a to b, inclusive.
(a, b) set from a to b, exclusive.
\[a, b) set from a (inclusive) to b (exclusive)

Set Unions are denoted with " U " and perform like this:
```
{ 1, 5, 8, 3 } U { 3, 2, 4, 8, 1 } = { 1, 5, 8, 3, 2 }
```
The resulting set is every element that exists in both sets (with no repetitions)

Set Intersections are denoted with upside down " U " and perform like this:
```
{ 1, 5, 8 } upside down U { 8, 5, 3, 4 } = { 1, 3, 4 }
```
The result is every element that does not exist in both sets. 

## Capital Sigma Notation
Often used to indicate a _Summation_. Not as complex as it seems, its basically just a for loop.\
![Capital Sigma Notation Example](https://github.com/RylanYancey/RylanYancey/blob/main/rust-docs-images/Screenshot_20220701_090517.png)\
Read this as: 
```cpp
for (int n = 1; n <= 6; n++) { output += n * 4; }
```

## Capital PI Notation
Just like the Capital Sigma, but indicates the product instead of a summation over elements.\
![Capital PI Notation Example](https://github.com/RylanYancey/RylanYancey/blob/main/rust-docs-images/Screenshot_20220701_091610.png)\
Read this as:
```cpp
for (int i = 1; i <= 10; i++) { output *= i; }
```

## Operations on Sets
Consider this notation:
```S <- { x^2 | x E S, x > 3 }```
Read this as:
Set S is equal to every element that belongs to set S, if x is greater than 3, squared. 

|S| is the cardinality operator, and returns the number of elements in S. 

## Max and Arg Max
The notation:
maxaEAf(a) returns the highest value f(a) for all elements in set A. 
argmaxaEAf(a) returns the element of the set that maximized f(a)

min and arg min are similar.

## Assignment Operator
-> assigns

##


