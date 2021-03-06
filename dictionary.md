# Dictionary

In **Python**, an **Object** is called **Dictionary**

**Same syntax:** 

**`{ Key: Value }`**

How to retrieve a value from a dictionary:

```python
numbers = {
    "One": 1,
    "Two": 2,
    "Three": 3
}

# retrieve 1
print(numbers["One"]) # 1

# Adding new items to dictionary
numbers["Four"] = 4

print(numbers)
# { "One": 1, "Two": 2, "Three": 3, "Four": 4 }

# Edit an item in a dictionary
numbers["One"] = "Uno"
# { "One": "Uno", "Two": 2, "Three": 3, "Four": 4 }

# Loop through a dictionary
for thing in numbers:
    print(thing)
# This will return only the keys:
    # One
    # Two
    # Three
    # Four

# To loop through values
for key in numbers:
    print(numbers[key])
# Result
    # Uno
    # 2
    # 3
    # 4

# Wipe an existing dictionary
numbers = {}
print(numbers) #{}
```

