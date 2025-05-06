# Object-Oriented Programming

## Overview
Object-Oriented Programming (OOP) is a paradigm based on the concept of objects.

### 📌 Topics Covered

1. Classes and Objects
2. Inheritance
3. Encapsulation
4. Polymorphism

### Classes and Objects
Classes are blueprints for creating objects.

```python
# Example
class Person:
    def __init__(self, name):
        self.name = name

    def greet(self):
        print(f"Hello, my name is {self.name}")

p = Person("Alice")
p.greet()
```

### Inheritance
Inheritance allows a class to derive properties from another class.

```python
# Example
class Animal:
    def speak(self):
        print("Animal speaks")

class Dog(Animal):
    def speak(self):
        print("Dog barks")

d = Dog()
d.speak()
```

### Encapsulation
Encapsulation restricts access to certain components.

```python
# Example
class BankAccount:
    def __init__(self):
        self.__balance = 0

    def deposit(self, amount):
        self.__balance += amount

    def get_balance(self):
        return self.__balance

account = BankAccount()
account.deposit(100)
print(account.get_balance())
```

### Polymorphism
Polymorphism allows methods to be used interchangeably between objects.

```python
# Example
class Bird:
    def fly(self):
        print("Bird flies")

class Airplane:
    def fly(self):
        print("Airplane flies")

def perform_fly(obj):
    obj.fly()

perform_fly(Bird())
perform_fly(Airplane())
```

