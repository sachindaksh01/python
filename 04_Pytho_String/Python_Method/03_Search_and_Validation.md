# Content Search and Validation:

+ [count()](#1-count-method-in-python-string)
+ [endswith()](#2-endswith-method-in-python-string)
+ [find()](https://www.w3schools.com/python/ref_string_find.asp)
+ [index()](https://www.w3schools.com/python/ref_string_index.asp)
+ [isalnum()](https://www.w3schools.com/python/ref_string_isalnum.asp)
+ [isalpha()](https://www.w3schools.com/python/ref_string_isalpha.asp)
+ [isascii()](https://www.w3schools.com/python/ref_string_isascii.asp)
+ [isdecimal()](https://www.w3schools.com/python/ref_string_isdecimal.asp)
+ [isdigit()](https://www.w3schools.com/python/ref_string_isdigit.asp)
+ [isidentifier()](https://www.w3schools.com/python/ref_string_isidentifier.asp)
+ [islower()](https://www.w3schools.com/python/ref_string_islower.asp)
+ [isnumeric()](https://www.w3schools.com/python/ref_string_isnumeric.asp)
+ [isprintable()](https://www.w3schools.com/python/ref_string_isprintable.asp)
+ [isspace()](https://www.w3schools.com/python/ref_string_isspace.asp)
+ [istitle()](https://www.w3schools.com/python/ref_string_istitle.asp)
+ [isupper()](https://www.w3schools.com/python/ref_string_isupper.asp)
+ [startswith()](https://www.w3schools.com/python/ref_string_startswith.asp)

  

## 1. count() Method in Python string
+ The count() method returns the number of times a specified value appears in the string.
  
```
Syntax
string.count(value, start, end)

--> Value Required. A String. The string to value to search for
--> Start Optional. An Integer. The position to start the search. Default is 0
--> end	Optional. An Integer. The position to end the search. Default is the end of the string

```


### Example: A
Return the number of times the value "apple" appears in the string:

```python
txt = "I love apples, apple are my favorite fruit"
x = txt.count("apple")
y = txt.count("apple", 10, 24)
print(x)
print(y)
```
### Output: A
```
2
1
```



## 2. endswith() Method in Python string
+ The endswith() method returns True if the string ends with the specified value, otherwise False.

  
```
Syntax
string.count(value, start, end)

--> Value Required. A String. The string to value to search for
--> Start Optional. An Integer. The position to start the search. Default is 0
--> end	Optional. An Integer. The position to end the search. Default is the end of the string

```


### Example: A
Check if the string ends with a punctuation sign (.):

```python
txt = "Hello, welcome to my world."
x = txt.endswith(".")
print(x)
```
### Output: A
```
True
```

### Example: B
Check if the string ends with the phrase "my world.":

```python
txt = "Hello, welcome to my world."
x = txt.endswith("my world.")
print(x)
```
### Output: B
```
True
```

### Example: c
Check if position 5 to 11 ends with the phrase "my world.":

```python
txt = "Hello, welcome to my world."
x = txt.endswith("my world.", 5, 11)
print(x)
```
### Output: c
```
False
```





