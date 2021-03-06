# Data Types

### String

* \*\*\*\*[**formatted string literals**](https://realpython.com/python-f-strings/)**\(f-strings\)**

  *  string literals that have an `f` at the beginning and curly braces containing expressions that will be replaced with their values

  ```python
  >>> name = "Eric"
  >>> age = 74
  >>> f"Hello, {name}. You are {age}."
  'Hello, Eric. You are 74.'

  # Capital F works as well
  >>> F"Hello, {name}. You are {age}."
  'Hello, Eric. You are 74.'
  ```

### Number

* **Positive** and N**egative** numbers are both considered as _**Integers**_
* Typically we would use **comma\(,\)** to separate large numbers. 
* Python instead uses **underscore** `_` to achieve the same thing.

```python
# Normal: 123, 456, 789
# Python: 123_456_789
```

#### Float

* Numbers with **decimals**
* Eg: **3.14159**

```python
# Important note:
# Float takes presedence over comma separators
print(734_529.678) # >734529.678 
```

### Type Conversion: str\(\) / int\(\) / float\(\)

```python
# Use type conversion to change one data type to another
num = "123"
print(num) # <class 'str'>

num = int(num)
print(num) # <class 'int'>

print(70 + float("100.5")) # 170.5 => data type is number
print(str(70) + str(100))  # "70100"  => data type is string
```

### **Boolean**

**True or False**

* They always **begin** with **capital** **T** for **True** and **F** for **False**

