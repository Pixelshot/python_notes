# Iteration

### When to use For or While Loop

* **For Loop: When you need to** _**do something**_ **with** _**each element**_ **that you're** _**iterating**_ **over**
* **While Loop: When you** _**don't care what number in the sequence**_ **you're in,** _**which item you're iterating**_ **through in a list and just** _**want to carry out some sort of functionality many times until the condition that you set has been met**_

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

### While Loop

* Condition **MUST BE TRUE**
  * This can be tricky when the variable/function that we're looping on is already true by default but needs to be false until the condition is met
  * Example of this is where [Reeborg](https://reeborg.ca/reeborg.html?lang=en&mode=python&menu=worlds%2Fmenus%2Freeborg_intro_en.json&name=Hurdle%202&url=worlds%2Ftutorial_en%2Fhurdle2.json) needs to keep moving until it reaches the flag at a random location  

```python
while something_is_true
    # Do something repeatedly

# For Reebog's example:
    while not at_goal():
        jump()
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

