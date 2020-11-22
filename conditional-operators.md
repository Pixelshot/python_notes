# Conditional Operators

### Syntax

```python
if condition:
    do this
else:
    do this
    
#Eg
water_level = 50
if water_level > 80:
    print("Drain water")
else:
    print("Continue")
```

#### Nested Syntax

```python
if condition1:
    if condition2:
    do something
    else:
    do something
else:
    do something
```

#### if / elif / else

```python
if condition1:
    do A
elif condition2:
    do B
else:
    do this
```

#### Multiple if

```python
if condition1:
    do A
if condition2:
    do B
if condition3:
    do C
```

* **Difference between Multiple & `elif` is that with multiple, each condition is independent from the other**

```python
# elif
if condition1: 
    do A 
elif condition2:
    do B
else:
    do C
# Only ONE of the conditions will run

# Multiple
if condition1:
    do A
if condition2:
    do B
if condition3:
    do C
```

#### Logical Operators

```python
A and B
C or D
not E
```



