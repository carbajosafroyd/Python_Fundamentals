Python Strings
Strings
Strings in python are surrounded by either single quotation marks, or double quotation marks.

'hello' is the same as "hello".

You can display a string literal with the print() function:

# Python Strings

## Strings

Strings in Python are surrounded by either single or double quotation marks.

```python
'hello' == "hello"
```

You can display a string literal with the `print()` function:

```python
print("Hello")
print('Hello')
```

## Quotes Inside Quotes

You can use quotes inside a string as long as they do not match the quotes surrounding the string:

```python
print("It's alright")
print("He is called 'Johnny'")
print('He is called "Johnny"')
```

## Assign a String to a Variable

Assigning a string to a variable is done with the variable name, followed by an equal sign and the string:

```python
a = "Hello"
print(a)
```

## Multiline Strings

You can assign a multiline string to a variable by using three quotes.

### Double Quotes

```python
a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)
```

### Single Quotes

```python
a = '''Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.'''
print(a)
```

The line breaks in the output appear at the same positions as they do in the code.

## Strings Are Arrays

Like many other popular programming languages, strings in Python are arrays of Unicode characters.

Python does not have a separate character data type. A single character is simply a string with a length of 1.

Square brackets can be used to access individual characters in a string. Remember that the first character has index `0`:

```python
a = "Hello, World!"
print(a[1])
```

## Loop Through a String

Since strings are arrays, you can loop through their characters with a `for` loop:

```python
for character in "banana":
    print(character)
```

## String Length

To get the length of a string, use the `len()` function:

```python
a = "Hello, World!"
print(len(a))
```

## Check Whether a String Contains Text

To check whether a phrase or character is present in a string, use the `in` keyword:

```python
txt = "The best things in life are free!"
print("free" in txt)
```

You can also use `in` in an `if` statement:

```python
txt = "The best things in life are free!"
if "free" in txt:
    print("Yes, 'free' is present.")
```

## Check Whether Text Is Missing

To check whether a phrase or character is not present in a string, use `not in`:

```python
txt = "The best things in life are free!"
print("expensive" not in txt)
```

You can also use `not in` in an `if` statement:

```python
txt = "The best things in life are free!"
if "expensive" not in txt:
    print("No, 'expensive' is not present.")
```