# 005_Outputing_Variables

## The Python ```print()``` function is often used to output variables.
###### Outputting a single variable
```python
x = "Python"
print(x)
```

## Outputting multiple variables
```python
x = "Python"
y = "Java"
z = "Typescript"
print(x, y, z)
```

## Alternative method
###### The ```+``` symbol can also be used in outputting multiple variables of the _same type_. 
###### However, this _does not apply_ to numeric variables where the output would be _compilled as the sum of the variables_. 
###### Using the ```+``` symbol to output multiple variables of different types would result in a type error and thus using the comma would be more adviced.
###### Using the ```+``` symbol to output strings would result in the string variables not having a space between each other.

###### Strings
```python
x = "Python "
y = "is "
z = "awesome"
print(x + y + z) # outputs "Pythonisawesome"
```
###### Numbers
```python
x = 1
y = 2
z = 3
print(x + y + z) # outputs 6
```
###### Type Error
```python
x = one
y = 2
z = three
print(x + y + z) # returns error with a return code of 1
```
## Suggestions
###### The best way to output multiple variables in the print() function is to separate them with commas, which supports ALL different data types

###### Example
```python
x = 5
y = "John"
print(x, y)
```

## Outputting Arrays

###### The array variables could be placed directly in the ```print()``` keyword and every element in the array would be printed

###### List
```python
array = ["I", "Love", "Python"]
print(array) #Prints ['I', 'Love', 'Python'] without formatting
```

## Formatting Arrays
###### If you want the elements in the array to be formatted like independent variables you would use something known as looping which is initially printing the elements in the array one by one.

```python
array = ["I", "Love", "Python"]
count = int(0)
while (count > len(array)):
    print(array[count])
    count += 1
```

##### @lemonscripting

