# Escape Characters

To insert characters that are normally difficult to use in a string, use an
escape character.

An escape character is a backslash (`\`) followed by the character you want to
insert.

## Escape Double Quotes

You will get a syntax error if you use unescaped double quotes inside a string
that is surrounded by double quotes:

```python
txt = "We are the so-called "Vikings" from the north."
```

Fix this by using the escape character (`\`) before each inner double quote:

```python
txt = "We are the so-called \"Vikings\" from the north."
print(txt)
```

## Common Escape Sequences

Other escape sequences used in Python include:

| Code | Result |
| --- | --- |
| `\'` | Single quote |
| `\\` | Backslash |
| `\n` | New line |
| `\r` | Carriage return |
| `\t` | Tab |
| `\b` | Backspace |
| `\f` | Form feed |
| `\ooo` | Octal value |
| `\xhh` | Hexadecimal value |