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
