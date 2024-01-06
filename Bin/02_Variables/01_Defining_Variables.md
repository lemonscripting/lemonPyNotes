# 01_Defining_Variables

## Creating variables
###### Not like most programming languages, Python has __no command__ for declaring a variable. A variable is created the moment you first assign a value to it.

###### Variables __do not__ need to be declared with any particular type, and can even __change type__ after they have been set.

###### For example
```python
x = 5
y = "John"
print(x)
print(y)
```

## Case sensitive
###### Variable names are case-sensitive and the below example of 'a' and 'A' will decalre two variables

```python
a = 4
A = "Sally"
#A will not overwrite a
```

## Strings
###### In Python the usage of single quotation marks and double quotation marks are the same 
```python
x = "John"
# is the same as
x = 'John'
```

## Casting
###### If you want to specify the data type of a variable, this can be done with casting.
```python
x = str(3)    # x will be '3'  | type = string
y = int(3)    # y will be 3    | type = integer
z = float(3)  # z will be 3.0  | type = float
```
###### Casting can also be used in conversion of datatypes

| Sample | Type | Conversion |
| ---------|----------|----------|
| x = "Hello World"	 | string | str() |
| x = 20 | integer | int() |
| x = 20.5 | float | float() |
| x = ["apple", "banana", "cherry"] | list | list() |
| x = ("apple", "banana", "cherry") | tuple | tuple() |
| x = range(6) | range | range() |
| x = {"name" : "John", "age" : 36} | dictionary | dict() |
| x = {"apple", "banana", "cherry"} | set | set() |
| x = frozenset({"apple", "banana", "cherry"}) | frozenset | frozenset() |
| x = True | boolean | bool() |

###### It is always a good habit to initialise your variables with casting for higher readability

## Get the Type
##### You can get the data type of a variable with the ```type()``` function.
###### For example
```python
x = 5
y = "John"
print(type(x))  # returns <class 'int'>  | type = string
print(type(y))  # returns <class 'str'>  | type = string 
```

##### @lemonscripting
