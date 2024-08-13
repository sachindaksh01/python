# Content Search and Validation:

+ [count()](#1-count-method-in-python-string)
+ [endswith()]()
+ [find()]()
+ [index()]()
+ [isalnum()]()
+ [isalpha()]()
+ [isascii()]()
+ [isdecimal()]()
+ [isdigit()]()
+ [isidentifier()]()
+ [islower()]()
+ [isnumeric()]()
+ [isprintable()]()
+ [isspace()]()
+ [istitle()]()
+ [isupper()]()
+ [startswith()]()

  

## 1. count() Method in Python string
+ The count() method returns the number of times a specified value appears in the string.
+ 
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
