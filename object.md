6. **Object:**

Objects are Python’s abstraction for data. All data in a Python program is represented by objects or by relations between objects. 
Every object has an identity, a type and a value. So, everything in Python is an object. Lists are objects. 42 is an object. Modules are objects. Functions are objects. Python bytecode is also kept in an object. All of these have types and unique IDs.

Example
Create a class named Person, use the __init__() function to assign values for name and age: class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

p1 = Person("John", 36)

print(p1.name)
print(p1.age)
