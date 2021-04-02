# Higher Order Functions

#### A function that can work with other function\(s\)

#### Example:

```python
def add(n1, n2):
    return n1 + n2

def subract(n1, n2):
    return n1 - n2

def multiply(n1, n2):
    return n1 * n2
    
def divide(n1, n2):
    return n1 / n2
    
def calculator(n1, n2, func):
    return func(n1,n2)
    
result = calculator(2, 3, add)
print(result) # > 5 
result = calculator(2, 3, divide)
print(result) # > 0 
result = calculator(2, 3, multiply)
print(result) # > 6 
```



