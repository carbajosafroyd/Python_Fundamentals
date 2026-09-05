# Modify Strings

Python has a set of built-in methods that you can use to modify strings.

## Uppercase

The `upper()` method returns the string in uppercase:

```python
a = "Hello, World!"
print(a.upper())
```

## Lowercase

The `lower()` method returns the string in lowercase:

```python
a = "Hello, World!"
print(a.lower())
```

## Remove Whitespace

Whitespace is the space before or after the actual text. The `strip()` method
removes whitespace from both ends of a string:

```python
a = " Hello, World! "
print(a.strip())  # Returns "Hello, World!"
```

## Replace a String

The `replace()` method replaces one string with another:

```python
a = "Hello, World!"
print(a.replace("H", "J"))
```

## Split a String

The `split()` method returns a list by dividing the string at each occurrence
of the specified separator:

```python
a = "Hello, World!"
print(a.split(","))  # Returns ['Hello', ' World!']
```