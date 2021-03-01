# OOP - Class

### A Class is the JOB. 

### An Object is the person RUNNING the job

#### eg: 

#### Class = Waiter

#### Object = Henry / Betty

**ATTRIBUTES: variables attribute to our modelled Object** 

**METHODS: a particular functions that an Object can do**

```python
# Use pass to let our Class/function remain empty

# The example class below will create an error because python expects something to be written in class therefore it wants user_1 to be indented inside of User
# class User:
  
# user_1 = User()

# We can use 'pass' keyword to solve this and let our Class/function remain empty
class User:
  pass

user_1 = User()
user_1.id = "001"
user_1.username = "hazri"

print(user_1.username)
```

#### Constructor

```python
# Syntax:
class (Name of the Class):
    # self = Class itself
    def __init__(self, attributes we define)
    # initialise attributes
    
# Example:
class User:
  def __init__(self, user_id, username):
    self.id = user_id
    self.username = username
    # How to set a default value. We don't need to put it as an argument. Just set it to 0 
    self.followers = 0
    self.following = 0
    
  def follow(self, user):
    self.following += 1
    user.followers += 1
    
user_1 = User("001", "matt")
user_2 = User("002", "jack")

user_1.follow(user_2)

print(user_1.followers)
print(user_1.following)

print(user_2.followers)
print(user_2.following)

```





