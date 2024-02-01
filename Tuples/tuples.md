# Tuples

Tuples are used to store multiple items in a single variable as like as list.

These tuples are unchangeable but lists are changeable.

Tuples are also ordered which maintains the insertion order as like as lists.

Tuples are written with round brackets `( )` .

```python
mytuple = (1, 2, 3)
print(mytuple)
#(1, 2, 3)
```

Accessing of items stored can be accessed with index positions.

It allows duplicate values.

If we create a tuple with only one item, it will not recognize as a tuple.

```python
mytuple = (1)
print(type(mytuple))
#<class 'int'>
```

### The tuple() Constructor:

This constructor is responsible to create new tuple.

```python
mytuple = tuple((1, 2, 3, 4))
print(mytuple)
#(1, 2, 3, 4)
```