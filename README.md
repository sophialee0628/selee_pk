# selee Package

**selee** is a python package that contains function `fizz_buzz()` in selee_module.

The `fizz_buzz()` function gets the input from a user and returns the output as string or the same type of the input as below logic:

- The multiples of 3 returns “Fizz” instead of the number
- The multiples of 5 return “Buzz”. 
- For positive integers which are multiples of both 3 and 5 return “FizzBuzz”
- Any other cases return the input

# Quick Start

This is a short introduction and quickstart for the `selee` package.

`fizz_buzz` application start with installing selee package 

## Examples
```
from selee import selee_module

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
Seven test cases to check the function is 
` python -m unittest tests/unit_test.py `