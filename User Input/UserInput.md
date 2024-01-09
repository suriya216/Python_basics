# User Input

User input refers to the process of obtaining a value from the user through input devices.

- Input devices, such as keyboards, mouse, scanners, etc.

******************************************For a single variable******************************************

```python
num = input()
print(num)
```

This **`input()`** function is responsible for the getting input from user. It waits for the user to respond via input devices.

****************For multiple variable****************

```python
X, Y = map(int, input().split())
Z = X + Y
print (Z)
```

- This **`split()`** method: Splits the input line into a list of substrings based on whitespace (spaces or tabs).
- This **`map(int, ...)`**: Applies the **`int`** function to each element of the list, converting them from strings to integers.
