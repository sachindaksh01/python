# Python Module Related to - Case Conversion:

+ capitalize()
+ casefold()
+ lower()
+ upper()
+ swapcase()
+ title()



## 1. capitalize() Method in python string
The capitalize() method returns a string where the first character is upper case, and the rest is lower case.

### Example : A
Upper case the first letter in this sentence:
```python
txt = "hello, and welcome to my world."
x = txt.capitalize()
print (x)
```
### Output : A
```
Hello, and welcome to my world.
```

### Example : B
```python
txt = "python is FUN!"
x = txt.capitalize()
print (x)
```
### Output : B
```
Python is fun!
```

## 2. casefold() Method in python string
+ The casefold() method returns a string where all the characters are lower case.
+ This method is similar to the lower() method, but the casefold() method is stronger, more aggressive, meaning that it will convert more characters into lower case, and will find more matches when comparing two strings and both are converted using the casefold() method.
### Example A
lower case all string:
```python
txt = "Hello, And Welcome To My World!"
x = txt.casefold()
print(x)
```
### Output
```
hello, and welcome to my world!
```


## 3. lower() Method in python string
+ The lower() method returns a string where all characters are lower case.
+ Symbols and Numbers are ignored.****
### Example : A
Lower case the string:
```python
txt = "Hello my FRIENDS"
x = txt.lower()
print(x)
```
### Output: A
```
hello my friends
```


## 4. upper() Method in python string
+ The upper() method returns a string where all characters are in upper case.
+ Symbols and Numbers are ignored.
### Example : A
Upper case the string:
```python
txt = "Hello my friends"
x = txt.upper()
print(x)
```
### Output: A
```
HELLO MY FRIENDS
```

## 5. swapcase() Method in python string
+ The swapcase() method returns a string where all the upper case letters are lower case and vice versa.
### Example : A
Make the lower case letters upper case and the upper case letters lower case:
```python
txt = "Hello My Name Is PETER"
x = txt.swapcase()
print(x)
```
### Output: A
```
hELLO mY nAME iS peter
```


## 6. title() Method in python string
+ The title() method returns a string where the first character in every word is upper case. Like a header, or a title.
+ If the word contains a number or a symbol, the first letter after that will be converted to upper case.

### Example : A
Make the first letter in each word upper case:
```python
txt = "Welcome to my world"
x = txt.title()
print(x)
```

### Output: A
```
Welcome To My World
```




