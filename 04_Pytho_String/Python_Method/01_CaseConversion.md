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
