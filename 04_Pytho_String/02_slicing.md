# Python - Slicing Strings

+ You can return a range of characters by using the slice syntax.
+ Specify the start index and the end index, separated by a colon, to return a part of the string


### Example
Get the characters from position 2 to position 5 (not included):

```python
b = "Hello, World!"
print(b[2:5])
```
### Output 
```
llo
```

> [!NOTE]
>  The first character has index 0.



## Slice From the Start
By leaving out the start index, the range will start at the first character:

### Example
Get the characters from the start to position 5 (not included):
```python
b = "Hello, World!"
print(b[:5])
```
### Output
```
Hello
```

## Slice To the End
By leaving out the end index, the range will go to the end:

### Example
Get the characters from position 2, and all the way to the end:
```python
b = "Hello, World!"
print(b[2:])
```
### Output
```
llo, World!
```


## Negative Indexing
Use negative indexes to start the slice from the end of the string:
### Example
+ Get the characters:
+ From: "o" in "World!" (position -5)
+ To, but not included: "d" in "World!" (position -2):
```python
b = "Hello, World!"
print(b[-5:-2])
```
## Output
```
orl
```










​
