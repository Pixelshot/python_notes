# Scope

#### Modifying Global Scope

* To modify a `global variable/function`, we use the `global` keyword 

```python
enemies = 1

def increase_enemies():
    global enemies # use global keyword to tell python that this is a global variable
    enemies += 1
    print(f"enemies inside function: {enemies}")
    
increase_enemies()
print(f"enemies outside function: {enemies}")

# Result:
# enemies inside function: 2
# enemies outside function: 2
```

* But using `global` is frowned upon and shouldn't be used frequently because it may create confusion especially when dealing with large number of code
* User `return` keyword instead

```python
enemies = 1

def increase_enemies():
    print(f"enemies inside function: {enemies}")
    return enemies + 1

enemies = increase_enemies()
print(f"enemies outside function: {enemies}")

# Result:
# enemies inside function: 1
# enemies outside function: 2
```

