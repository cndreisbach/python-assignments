<<<<<<< HEAD
# Approximate a square root

## Description

Write a program that asks the user for a positive number and then outputs the
approximated square root of the number. Use Newton's method to find the square
root, with epsilon = 0.01.

## Objectives

### Learning Objectives

After completing this assignment, you should understand:

* How variables work
* How `while` works
* The concept of successive approximation

### Performance Objectives

After completing this assignment, you should be able to:

* Write a Python script
* Ask for input
* Print output

## Details

### Deliverables

* A GitHub repo called approximate-square-root containing at least:
  * This `README.md` file
  * a file called `square_root.py`

### Requirements  

Here is an example of the program running correctly:

```
$ python square_root.py
Enter a positive number: 4
The square root of 4 is 2.0.

$ python square_root.py
Enter a positive number: 20
The square root of 20 is 4.472137791286727.
```

Your program will be tested with the script `test.sh`. To run this script, run
`brew install roundup` first.

## Normal Mode

Newton's method of successive approximations says that whenever we have a guess
`y` for the value of the square root of a number `x`, we can get a better guess
(one closer to the actual square root) by averaging `y` with `x/y`. If we do
this over and over, we should be able to get a very accurate guess.

You have to write a script that asks the user for a positive number and then
compute the square root with a maximum error of 0.01. You then print out your
answer to the user.

## Hard Mode

In each iteration of your loop, print out the current number of iterations and
the current guess.

Examine the input into your program and give an appropriate error message if
a non-number or negative number is given.

## Extra Hard Mode

Look up [complex numbers in Python][]. Allow negative numbers as input into
your program.

## Additional Resources

* Read more about [the Babylonian/Newton's method of approximating square roots](https://en.wikipedia.org/wiki/Methods_of_computing_square_roots#Babylonian_method).
* [Numeric types in Python](https://docs.python.org/3/library/stdtypes.html#numeric-types-int-float-complex).

## Credit

This assignment is adapted from
[SICP](https://mitpress.mit.edu/sicp/chapter1/node9.html) by Abelson and
Sussman.


[complex numbers in Python]: https://docs.python.org/3/library/stdtypes.html#numeric-types-int-float-complex
=======
# Curriculum for Jan 2015 Python course at TIY Durham

## Timeline

### [Week 1](week1.md)

By the end of this week, students should be comfortable with:

* Computational thinking
* Setting up your computer for development
* Variables
* Loops
* Functions
* Modules
* Dictionaries
* Testing your code
* Using Git and GitHub to manage source code

#### References:

* [Notebooks](notebooks/week1)
* Chapters 1-5 in [I2CPUP][].

### [Week 2](week2.md)

* Debugging
* Tuples
* Higher-order functions
* Recursion
* Exceptions
* Object-oriented programming
* Algorithmic complexity
* Search and sort algorithms

#### References:

* Chapters 6-10 in [I2CPUP][].

### [Week 3](week3.md)

* Stochastic programming
* Randomness
* Creating simulations
* Monte Carlo simulations
* Plotting
* NumPy
* Simple statistics
* Basic statistical inquiry

#### References:

* Chapters 11-14 in [I2CPUP][].

### [Week 4](week4.md)

* Loading and manipulating data with pandas
* Common data formats
* Publicly available data sets
* Data set quality
* Cleaning data sets
* Relational databases
* Database design

#### References

* [Python for Data Analysis](http://shop.oreilly.com/product/0636920023784.do)

### Week 5: Data

* Consuming REST APIs
* Neural networks
* Classification algorithms
* Clustering
* Recommendation algorithms

#### References

* Chapter 19 in [I2CPUP][].

### Week 6: Web

* HTML
* CSS
* Flask
* REST

### Week 7: Web

* JavaScript
* Web dataviz

### Week 8: Systems

* Linux
* Installing packages
* Running programs remotely
* Supervisors
* Ansible

### Week 9

This week is a week for review and catch-up. Things will fall through the cracks during the previous 8 weeks, and so we have this week as a flex week to make sure we cover everything you need.

[I2CPUP]: https://mitpress.mit.edu/books/introduction-computation-and-programming-using-python-0
>>>>>>> 7e93f19126f7a12ccfa9940d67696a87b5108f44
