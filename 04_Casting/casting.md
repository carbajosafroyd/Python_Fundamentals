# Python Casting

## Specify a Variable Type

There may be times when you want to specify a type for a variable. This can be done with **casting**. Python is an object-oriented language, and it uses classes to define data types, including its primitive types.

Casting in Python is done using constructor functions:

- `int()` constructs an integer from an integer, a float (by removing the decimal part), or a string that represents a whole number.
- `float()` constructs a floating-point number from an integer, a float, or a string that represents a number.
- `str()` constructs a string from a wide variety of data types, including strings, integers, and floats.

## Integers

```python
x = int(1)      # x will be 1
y = int(2.8)    # y will be 2
z = int("3")    # z will be 3
```

## Floats

```python
x = float(1)      # x will be 1.0
y = float(2.8)    # y will be 2.8
z = float("3")    # z will be 3.0
w = float("4.2")  # w will be 4.2
```

## Strings

```python
x = str("s1")  # x will be "s1"
y = str(2)     # y will be "2"
z = str(3.0)   # z will be "3.0"
```