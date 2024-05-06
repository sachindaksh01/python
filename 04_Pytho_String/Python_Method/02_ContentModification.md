# Python Module Related to - Content Modification:

+ center()
+ expandtabs()
+ join()
+ ljust()
+ partition()
+ replace()
+ rjust()
+ rsplit()
+ rstrip()
+ lstrip()
+ split()
+ splitlines()
+ strip()
+ zfill()


## 1. center() Method in Python string
The center() method will center align the string, using a specified character (space is default) as the fill character.


### Example : A
Print the word "banana", taking up the space of 20 characters, with "banana" in the middle:
```python
txt = "banana"
x = txt.center(20)
print(x)
```
### Output: A
```
    banana
```


## 2. expandtabs() Method in Python string
The expandtabs() method sets the tab size to the specified number of whitespaces.

### Example : A
Set the tab size to 2 whitespace:

```python
txt = "H\te\tl\tl\to"
x =  txt.expandtabs(5)
print(x)

```
### Output: A
```
H    e    l    l    o
```


## 3. join() Method in Python string
+ The join() method takes all items in an iterable and joins them into one string.
+ A string must be specified as the separator.

### Example : A
Join all items in a tuple into a string, using a hash character as separator:

```python
myTuple = ("John", "Peter", "Vicky")
x = "#".join(myTuple)
print(x)

```
### Output: A
```
John#Peter#Vicky
```


## 4. ljust() Method in Python string
+ The ljust() method will left align the string, using a specified character (space is default) as the fill character.

### Example : A
Return a 20 characters long, left justified version of the word "banana":

```python
txt = "banana"
x = txt.ljust(20)
print(x, "is my favorite fruit.")

```
### Output: A
```
banana              is my favorite fruit.
```


## 5. partition() Method in Python string
+ The partition() method searches for a specified string, and splits the string into a tuple containing three elements.
+ The first element contains the part before the specified string.
+ The second element contains the specified string.
+ The third element contains the part after the string.

### Example : A
Search for the word "bananas", and return a tuple with three elements:
+ 1 - everything before the "match"
+ 2 - the "match"
+ 3 - everything after the "match"
+ 
```python
txt = "I could eat bananas all day"
x = txt.partition("bananas")
print(x)
```
### Output: A
```
('I could eat ', 'bananas', ' all day')
```




## 6. replace() Method in Python string
+ The replace() method replaces a specified phrase with another specified phrase.
+ Note: All occurrences of the specified phrase will be replaced, if nothing else is specified.

### Example : A
+ Replace the word "bananas":

```python
txt = "I like bananas"
x = txt.replace("bananas", "apples")
print(x)

```
### Output: A
```
I like apples
```



## 7. rjust() Method in Python string
+ Note: In the result, there are actually 14 whitespaces to the left of the word banana.
+ The rjust() method will right align the string, using a specified character (space is default) as the fill character.

### Example : A
+ Return a 20 characters long, right justified version of the word "banana":


```python
txt = "banana"
x = txt.rjust(20)
print(x, "is my favorite fruit.")

```
### Output: A
```
              banana is my favorite fruit.
```




## 8. rsplit() Method in Python string
+ The rsplit() method splits a string into a list, starting from the right.
+ If no "max" is specified, this method will return the same as the split() method.
+ Note: When maxsplit is specified, the list will contain the specified number of elements plus one.

### Example : A
Split a string into a list, using comma, followed by a space (, ) as the separator:



```python
txt = "apple, banana, cherry"
x = txt.rsplit(",+ ")
print(x)

```
### Output: A
```
['apple, banana, cherry']
```



## 9. rstrip() Method in Python string
The rstrip() method removes any trailing characters (characters at the end a string), space is the default trailing character to remove.

### Example : A
Remove any white spaces at the end of the string:

```python
txt = "     banana     "
x = txt.rstrip()
print("of all fruits", x, "is my favorite")

```
### Output: A
```
of all fruits     banana is my favorite
```



## 10. lstrip() Method in Python string
The lstrip() method removes any leading characters (space is the default leading character to remove)

### Example : A
Remove spaces to the left of the string:

```python
txt = "     banana     "
x = txt.lstrip()
print("of all fruits", x, "is my favorite")

```
### Output: A
```
of all fruits banana     is my favorite
```



