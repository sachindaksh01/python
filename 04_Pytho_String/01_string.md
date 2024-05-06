# Python Strings

Strings in python are surrounded by either single quotation marks, or double quotation marks.
'hello' is the same as "hello".
You can display a string literal with the print() function:

### Example : 1
```python
print("Hello")
print('Hello')
```
### Output
```
Hello
Hello
```

##  Quotes Inside Quotes
You can use quotes inside a string, as long as they don't match the quotes surrounding the string:

 ### Example
 ```python 
print("It's alright")
print("He is called 'Johnny'")
print('He is called "Johnny"')
```
### Output
```
It's alright
He is called 'Johnny'
He is called "Johnny"
```

## Assign String to a Variable
Assigning a string to a variable is done with the variable name followed by an equal sign and the string:

### Example
```python
a = "Hello"
print(a)
```
### Output
```
Hello
```

## Multiline Strings
You can assign a multiline string to a variable by using three quotes:

### Example
You can use three double quotes: or single quotes: 
``` python
a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)

```
### Output
```
Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.
```

