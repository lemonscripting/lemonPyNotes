# 03_Mass_Assigning

## Many Values to Multiple Variables
###### Python allows you to assign values to multiple variables in one line:
###### Note: Make sure the number of variables matches the number of values, or else you will get an error.
```python
x, y, z = "red", "yellow", "blue"
print(x)
print(y)
print(z)
```

## One Values to Multiple Variables
###### Python allows you to assign one value to multiple variables in one line:
```python
x = y = z = "red"
print(x)
print(y)
print(z)
```

## Unpack a Collection
###### Python allows you to assign one value to multiple variables in one line:
###### This methods works for ALL array structured variables
###### List
```python
colours = ["red", "yellow", "blue"]
x, y, z = colours
print(x)
print(y)
print(z)
```
###### Tuple
```python
colours = ("red", "yellow", "blue")
x, y, z = colours
print(x)
print(y)
print(z)
```

###### Set
```python
colours = {"red", "yellow", "blue"}
x, y, z = colours
print(x)
print(y)
print(z)
```

##### @lemonscripting

