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

### Ensure all conditions are at the top of the if statements first

```python
# Eg: FizzBuzz challenge
# 3 conditions have to be met:
    # 1. Number is divisible by 3
    # 2. Number is divisible by 5
    # 3. Number is divisible by 3 AND 5

# Condition #3 must be the first condition in our if/else statement 
# This is because if/elif statement will STOP once it's found the first statement that returns true
# If we put in condition #1 or #2 first then it'll immediately stop once it's found the first number that meets the criteria and skips the rest of the elif statements
# Therefore our statement should look like this:

 for num in range(1, 101):
    if num % 3 == 0 and num % 5 == 0:
        print("FizzBuzz")
    elif num % 3 == 0:
        print("Fizz")
    elif num % 5 == 0:
        print("Buzz")
    else:
        print(num)
 
```

