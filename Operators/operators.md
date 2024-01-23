# Operators

In Python, operators are special symbols or keywords that perform operations on operands. Operands can be variables, values, or expressions. Python supports various types of operators,

- **Arithmetic Operators**

```python
add = X + Y   # addition of two numbers
sub = X - Y   # subtraction of two numbers
mul = X * Y   # multiplication of two numbers
div = X // Y  # division of two numbers (Floor division)
# By using double slash '//' it returns the quotient in int datatype.
# Single slash will return the floating point value for the quotient.
mod = X % Y   # Operator used to find the remainder
power = X ** Y    # Power of two numbers

```

- **Comparison (Relational) Operators**

```python
x, y = 5, 10
#Relational operators return boolean values
print(x == y)   #False
print(x != y)   #True
print(x < y)    #True
print(x > y)    #False
print(x <= y)   #True
print(x >= y)   #False
```

- **Logical Operators**

```python
isHot = True
isSweet = True
if isHot and isSweet:
    print("It's a tea!")
elif not(isHot) and isSweet:
    print("It's a juice!")
else:
    print("It's a soup!")
#As same for OR operator.
```

- **Assignment Operators**

```python
a = 3
b = 5
a += b    # a = a + b
print(a)
#Same for '-=', '*=', '/=', '%=' etc.
```

- **Identity Operators**

```python
a = 3
b = 2
print(a is b)   #False
print(a is not b)   #True
#If the values same it returns true, else false.
```

- **Membership Operators**

```python
a = "SURIYA"
print("S" in a) #True
print("Z" in a) #False
#If the sequence specified present 
#in the value returns True, otherwise False.
```
