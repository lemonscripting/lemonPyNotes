# 006_Variable_Scopes

###### In Python, a scope refers to the region of a program where a particular variable is defined and can be accessed. In general, Python has two main types of scopes, Global and Local.

## Global Scope
- Variables defined outside of any function or class have a global scope.
- They can be accessed and modified from anywhere in the code, both inside and outside functions or classes.
- Can be interpreted as the "ROOT DIRECTORY" of the codes
###### A global variable can be accessed anywhere throughout the code
```python
a = 100
def function():
    print(a)
function()  # outputs 100
```

## Global Keyword
###### If you want to modify a global variable from inner scopes of the code, you can use the ```global``` keyword which acts as a hook connecting inner scopes and the "ROOT DIRECTORY" of the code.

```python
a = 100

def function():
    global a  # Declare 'a' as a global variable
    print(a)
    a += 100
    print(a)

function()  # This will output 100 and 200

# Now, you can use 'a' as a global variable outside the function
print(a)  # This will output 200
```

## Local Scope
###### A variable in a local scope can only be modified within the local scope and attempting to modify it outside the scope will result in a error.
```python
def my_function():
    local_variable = 50
    print(local_variable)

my_function()  # This will print 50

# Trying to access local_variable outside the function will result in an error
# print(local_variable)  # This line will raise a NameError
```

## NOTE
###### There IS a DIFFERENCE between "ACCESSING" and "MODIFYING" a variable. 
###### "ACCESSING" in this case refers to the ability to print the variables and NOT the ability to perform actions using the variable or to manipulate the variable
###### "MODIFYING" in this case refers to FULL CONTROL over the variable and any desired action can be taken on it

###### As mentioned,```global variable_name``` can be declared in an inner scope to change the variable from a local variable to be a global variable.

##### @lemonscripting

