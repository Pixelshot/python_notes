# Scope

#### Modifying Global Scope

* To modify a `global variable/function`, we use the `global` keyword 

```python
enemies = 1

def increase_enemies():
    global enemies # use global keyword to tell python that this is a global variable
    enemies += 1
    print(f"enemies inside function: {enemies}"}
    
increase_enemies()
print(f"enemies outside function: {enemies}")
```

