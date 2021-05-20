# selee_pk Package

**selee_pk** is a python package that contains the function `fizz_buzz()` in selee_module.

The `fizz_buzz()` function accepts a single argument, x and returns the output as string or the same type of the input x, using the below logic:

- Multiples of 3 returns “Fizz” instead of the number
- Multiples of 5 return “Buzz”. 
- For integers which are multiples of both 3 and 5 return “FizzBuzz”
- Any other cases return the input

# Installation

Python>=3.6 is needed.

`pip install selee_pk`

# Quick Start

This is a short introduction and quickstart for the `selee_pk` package.

`fizz_buzz` application starts by installing selee package 

`from selee_pk import selee_module`

Users can check the result of the `fizz_buzz` function by putting the input x inside the parentheses.

`selee_module.fizzbuzz(x)`

## Examples
```
from selee_pk import selee_module

selee_module.fizzbuzz(2)
 >> 2
selee_module.fizzbuzz(3)
 >> Fizz
selee_module.fizzbuzz(5)
 >> Buzz
 selee_module.fizzbuzz(15)
 >> FizzBuzz
```

# Test
Seven test cases are included in the `unit_test.py`.
Below is the code for running those test cases.

` python -m unittest tests/unit_test.py `
