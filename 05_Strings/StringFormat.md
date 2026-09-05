# String Formatting

As we learned in the Python Variables chapter, you cannot directly combine
strings and numbers with the `+` operator:

```python
age = 36
txt = "My name is John, I am " + age  # This produces a TypeError.
print(txt)
```

You can combine strings and numbers by using f-strings or the `format()`
method.

## F-Strings

F-strings were introduced in Python 3.6 and are now the preferred way to
format strings.

To create an f-string, put an `f` before the string literal and add curly
braces (`{}`) as placeholders for variables or other expressions.

### Insert a Variable

```python
age = 36
txt = f"My name is John, I am {age}"
print(txt)
```

### Use Placeholders and Modifiers

A placeholder can contain variables, operations, functions, and format
modifiers:

```python
price = 59
txt = f"The price is {price} dollars"
print(txt)
```

A modifier follows a colon. For example, `.2f` formats a number with two
decimal places:

```python
price = 59
txt = f"The price is {price:.2f} dollars"
print(txt)
```

### Perform an Operation

A placeholder can contain Python code, such as a math operation:

```python
txt = f"The price is {20 * 59} dollars"
print(txt)
```