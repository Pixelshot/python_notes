# Notes

#### Print to console

```python
print("Hello World!")

# String Concatenation
print("Hello" + " " + "there")

#Use \n for a new line
print("Hello \nthere!")
# > Hello
# > there!
```

#### input\(\)

```python
input("A prompt for the user")

# Usage:
print("Hello " + input("What is your name?"))

# Console
# What is your name?Bob
# Hello Bob
```

**Subscript**

```python
# The act of pulling out a particular element from a string
print("Hello"[4]) # returns o
```

#### Type Checking: type\(\)

```python
# To check the type of data 
# Equivalent to typeOf in JavaScript
name = "Bob"
print(name) #returns <class 'str'>
```

#### Type Conversion: str\(\) / int\(\) / float\(\)

```python
# Use type conversion to change one data type to another
num = "123"
print(num) # <class 'str'>

num = int(num)
print(num) # <class 'int'>

print(70 + float("100.5")) # 170.5 => data type is number
print(str(70) + str(100))  # "70100"  => data type is string
```

#### [floor division //](https://www.w3schools.com/python/ref_math_floor.asp)

* **Round numbers down to the nearest integer**

```python
print(math.floor(0.6)) # 0
print(math.floor(1.4)) # 1
print(math.floor(5.3)) # 5
print(math.floor(-5.3)) # -6 
print(math.floor(22.6)) # 22
print(math.floor(10.0)) # 10
```

#### function\(\)

* **Remember the fries, rock & machine analogy**



