# Conditional Statements

If-Else statements in Python are part of conditional statements, which decide the control of code.

Python supports the usual logical conditions from mathematics which are responsible for the control of code.

- Equals:  `a == b`
- Not Equals:  `a != b`
- Less Than:  `a < b`
- Greater Than:  `a > b`
- Less Than or Equals to:  `a <= b`
- Greater Than or Equals to:  `a >= b`

These conditions can be used in several ways, most commonly in "if statements" and loops.

```python
a = 10
b = 20
if a == b:
    print("'a' and 'b' are same")
else:
    print("'a' and 'b' are different")

#'a' and 'b' are different
```
Conditional statements are if, elif and else statements to control code.

```python
if condition:   #This condition checks if it is true enters the block.
    #code blocks...
elif conition:  #If the previos condition were not true then checks with this condition.
    #code blocks...
else:   #If all the above conditions were not true then enters the final block. 
    #code blocks...
```

The above conditions can be written in short handed also,

- Short Hand If
    
    ```python
    if a > b: print("'a' is greater than 'b'")
    ```
    
- Short  Hand If .. Else

```python
a = 10
b = 20
print("'a' and 'b' are same") if a == b else print("'a' and 'b' are different")
#'a' and 'b' are different
```

This technique is also known as **Ternary Expression.**

We can also use bitwise operators to check conditional statements.

**Nested If**

We can use if statements inside the if statements, this is called as nested if statements.

```python
a = 10
b = 20

if a > 5:
    print("'a' is greater than 5")
    if b > 10:
        print("'b' is greater than 10")
#'a' is greater than 5
#'b' is greater than 10
```

**The pass Statement**

if statements cannot be empty, but for some reason you have to leave it with no content. It tends to getting an error, to avoid error use pass statement

```python
a = 10
b = 20

if a > 5:
    pass
    if b > 10:
        print("'b' is greater than 10")
#'b' is greater than 10
```
