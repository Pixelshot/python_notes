# Data Structure: Array / List

#### Difference between an Array & List is:

* **Array: contents of an array must be the same type.**
* **List: contents can be mixed, making it more flexible.**

#### How to change/update an element inside of a array/list:

```python
fruits = ["apple", "oragne", "grape"]

fruits[1] = "orange"

print(fruits)
> ['apple', 'orange', 'grape']
```

#### Add ONE element inside of a list with .append\(\)

```python
fruits.append("pear")

print(fruits)
> ['apple', 'orange', 'grape', 'pear']
```

#### Adding MULTIPLE elements inside of a list with .extend\(\)

* **This method only takes ONE ARGUMENT so if we have multiple elements we can turn it into a list**

```python
more_fruits = ["mango", "banana", "papaya"]
fruits.extend(more_fruits)

print(fruits)
> ['apple', 'orange', 'grape', 'pear', 'mango', 'banana', 'papaya']
```

#### Nested List

```python
fruits = ["Strawberry", "Nectarines", "Apples", "Grapes", "Peaches", "Cherries", "Pears"]
vegetables = ["Spinach", "Kale", "Tomatoes", "Celery", "Potatoes"]

dirty_dozen = [fruits, vegetables]
```



