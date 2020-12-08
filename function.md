# Function

### Syntax

```python
# Name of function followed with ()
function()
```

[Built-in functions](https://docs.python.org/3/library/functions.html)

#### Syntax for creating our own function

```python
def my_function():
    # Do stuff
    
# Call the function
my_function()
```

#### Functions with Inputs

```python
def my_function(something): # something in this line is called Parameter
    # Do this with something
    # Then do this
    # Finally do this
    
my_function(123) # 123 is the Argument
```

#### Positional Arguments

```python
def my_function(a, b, c):
    # Do this with a
    # Then do his with b
    # Finally do this with c

my_function(1, 2, 3)
# a = 1
# b = 2
# c = 3

# If we swap positions 3 & 1:
my_function(3, 2, 1):
# a = 3
# b = 2
# c = 1

# The order of where we put our arguments matter
# To change this behaviour, we use Keyword Arguments 
```

#### Keyword Arguments

```python
# Keyword Arguments lock each argument to it's assigned key
def my_function(a=1, b=2, c=3)
def my_function(c=3, b=2, a=1)
# both of the function calls above will return the same output now 
```

