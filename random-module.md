# Random Module

### [Random Integer](https://www.askpython.com/python-modules/python-random-module-generate-random-numbers-sequences)

#### 1. randrange\(start, stop, step\)

Returns a randomly selected integer from `range(start, stop, step)`. This raises a `ValueError` if `start` &gt; `stop`.

#### 2. randint\(a, b\)

Returns a random integer between **a** and **b** \(both inclusive\). This also raises a `ValueError` if `a` &gt; `b`.

Here is an example that illustrates both the above functions.

```python
import random
 
i = 100
j = 20e7
 
# Generates a random number between i and j
a = random.randrange(i, j)
try:
    b = random.randrange(j, i)
except ValueError:
    print('ValueError on randrange() since start > stop')
 
c = random.randint(100, 200)
try:
    d = random.randint(200, 100)
except ValueError:
    print('ValueError on randint() since 200 > 100')
 
print('i =', i, ' and j =', j)
print('randrange() generated number:', a)
print('randint() generated number:', c)
```

#### 3. random.**random**\(\) 

Returns the next random **floating** point number between **\[0.0 to 1.0\] but does not include 1**

#### 3. [random.**seed**\(\) ](https://www.w3schools.com/python/ref_random_seed.asp)

This method is useful when we want our **variable** to **keep** the **same** random number





