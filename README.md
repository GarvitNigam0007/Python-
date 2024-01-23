# Python-
Some topics of python
Functional Programming 
Functional programming is a style of programming that (as the name suggests) is based around functions. 

A key part of functional programming is higher-order functions. Higher-order functions take other functions as arguments, or return them as results.

Example:

CODE PLAYGROUND: PY
def apply_twice(func, arg):
   return func(func(arg))

def add_five(x):
   return x + 5

print(apply_twice(add_five, 10))

The function apply_twice takes another function as its argument, and calls it twice inside its body.



def test(func, arg):
  return func(func(arg))

def mult(x):
  return x * x

print(test(mult, 2))

Explanation: def test(func, arg): return func(func(arg)) def mult(x): return x * x print(test(mult, 2)) test and mult — are function names. func, arg — are the names of arguments. print function asks as to output test function with the given arguments: mult, 2 If we do this, we get: def test(mult, 2): return mult(mult(2)) This now asks us to do mult function twice, since there are 2 names of the second function present. If we do this, we get; 1. 2 * 2 = 4 2. 4 * 4 = 16 Therefore, the answer is 16, since we did what print() function have asked us to do, and we followed the statements in both functions
