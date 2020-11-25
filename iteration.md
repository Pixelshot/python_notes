# Iteration

### For Loop

```python
for item in list_of_items:
    # Do something to each item
    
fruits = ["Apple", "Peach", "Pear"]

for fruit in fruits:
    print(fruit)
# Apple
# Peach
# Pear
```

### Range

 [**range**_**\(start, stop, step**_**\)**](https://www.w3schools.com/python/ref_func_range.asp)\*\*\*\*

```python
for number in range(a, b):
print(number)

# Sum of all numbers from 1 to 100
total = 0
for number in range(1, 101):
    total += number
print(total)
# > 5050

# Sum of all even numbers from 1 to 100
sum = 0
for number in range(2, 101, 2):
    sum += number
print(sum)
# > 2550

# Using modulo to calculate all even numbers
for number in range(1, 101):
    if number % 2 == 0:
        sum += number

print(sum)
```

