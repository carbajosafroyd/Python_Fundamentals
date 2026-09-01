# Froyd Carbajosa
# Python Numbers

Python supports three numeric types for mathematical operations and data representation:

- **int** - Integer numbers
- **float** - Floating-point numbers  
- **complex** - Complex numbers

---

## Creating Numeric Variables

Variables of numeric types are created when you assign a value to them:

```python
x = 1    # int
y = 2.8  # float
z = 1j   # complex
```

To verify the type of any object in Python, use the `type()` function:

```python
print(type(x))  # <class 'int'>
print(type(y))  # <class 'float'>
print(type(z))  # <class 'complex'>
```

---

## Integers (int)

An **integer** is a whole number, positive or negative, without decimals, and has unlimited length.

### Example: Integer Values

```python
x = 1
y = 35656222554887711
z = -3255522

print(type(x))  # <class 'int'>
print(type(y))  # <class 'int'>
print(type(z))  # <class 'int'>
```

---

## Floating-Point Numbers (float)

A **float** (floating-point number) is a number, positive or negative, containing one or more decimals.

### Example: Decimal Numbers

```python
x = 1.10
y = 1.0
z = -35.59

print(type(x))  # <class 'float'>
print(type(y))  # <class 'float'>
print(type(z))  # <class 'float'>
```

### Example: Scientific Notation

Floats can also be expressed using scientific notation with an "e" to indicate the power of 10:

```python
x = 35e3      # 35000.0
y = 12E4      # 120000.0
z = -87.7e100 # -8.77e+101

print(type(x))  # <class 'float'>
print(type(y))  # <class 'float'>
print(type(z))  # <class 'float'>
```

---

## Complex Numbers (complex)

**Complex numbers** are written with a "j" as the imaginary part:

```python
x = 3+5j
y = 5j
z = -5j

print(type(x))  # <class 'complex'>
print(type(y))  # <class 'complex'>
print(type(z))  # <class 'complex'>
```

---

## Type Conversion

You can convert between numeric types using the `int()`, `float()`, and `complex()` functions:

### Example: Converting Between Types

```python
x = 1      # int
y = 2.8    # float
z = 1j     # complex

# Convert from int to float
a = float(x)

# Convert from float to int
b = int(y)

# Convert from int to complex
c = complex(x)

print(a)  # 1.0
print(b)  # 2
print(c)  # (1+0j)

print(type(a))  # <class 'float'>
print(type(b))  # <class 'int'>
print(type(c))  # <class 'complex'>
```

**Note:** Complex numbers cannot be converted into another number type.

---

## Random Numbers

Python does not have a built-in `random()` function, but Python provides a `random` module that can be used to generate random numbers:
