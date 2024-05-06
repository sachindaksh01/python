#  Variables and Data Types
## What is a variable?
The variable is like a container that holds data. Very similar to how our containers in kitchen holds sugar, salt etc
Creating a variable is like creating a placeholder in memory and assigning it some value. In Python its as easy as writing:
```python
a = 1
b = True
c = "Harry"
d = None
```

##  Variable Names
+ A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:
+ A variable name must start with a letter or the underscore character
+ A variable name cannot start with a number
+ A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
+ Variable names are case-sensitive (age, Age and AGE are three different variables)
+ A variable name cannot be any of the Python keywords.

## Python Variables - Assign Multiple Values
###  Many Values to Multiple Variables
+ Python allows you to assign values to multiple variables in one line:
```python
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)

```

### One Value to Multiple Variables
And you can assign the same value to multiple variables in one line:
```python
x = y = z = "Orange"
print(x)
print(y)
print(z)
```

### Unpack a Collection
If you have a collection of values in a list, tuple etc. Python allows you to extract the values into variables. This is called unpacking.

```python
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
print(x)
print(y)
print(z)

```

























