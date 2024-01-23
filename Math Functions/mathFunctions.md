# Math Functions

Python has a built-in module that you can use for mathematical tasks.

The `math` module has a set of methods and constants.

- **math.ceil():**
    
    Rounds a number up to the nearest integer.
    
    ```python
    import math
    a = 3.7
    print(math.ceil(a)) #4
    b = 99.3
    print(math.ceil(b)) #100
    ```
    
- **math.floor():**
    
    Rounds a number down to the nearest integer.
    
    ```python
    import math
    a = 3.7
    print(math.floor(a)) #3
    b = 99.3
    print(math.floor(b)) #99
    ```
    
- **math.gcd():**
    
    Returns the greatest common divisor of two integers.
    
    ```python
    import math
    a = 4
    b = 8
    print(math.gcd(a, b))  #4
    ```
    
- **math.log10():**
    
    Returns the base-10 logarithm of x.
    
    ```python
    import math
    a = 100
    print(math.log10(a))  #2.0
    #returns as a floating point value
    ```
    
    Similarly for base-2 logarithm is also available.
    
- **math.pow():**
    
    Returns the value of x to the power of y.
    
    ```python
    import math
    a = 2
    b = 3
    print(math.pow(a, b))  #8.0
    #returns as a floating point value
    ```
    
- **math.sqrt():**
    
    Returns the square root of a number.
    
    ```python
    import math
    a = 8
    print(math.sqrt(a))  #2.8284271247461903
    print(math.isqrt(a))  #2 
    #math.isqrt() Rounds a square root number 
    #downwards to the nearest integer
    ```
    

There are many methods present in the math library, similar to this.
