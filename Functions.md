# Functions

## Overview
Functions are reusable blocks of code that perform specific tasks.

### Topics Covered

1. Defining Functions
2. Parameters and Arguments
3. Return Statements
4. Lambda Functions

### Defining Functions
Functions are defined using the `def` keyword.

```python
# Example
def greet():
    print("Hello!")

greet()
```

### Parameters and Arguments
Functions can accept inputs to customize their behavior.

```python
# Example
def greet(name):
    print(f"Hello, {name}!")

greet("Alice")
```

### Return Statements
Functions can return values using the `return` keyword.

```python
# Example
def add(x, y):
    return x + y

result = add(3, 5)
print(result)
```

### Lambda Functions
Lambda functions are anonymous functions defined with the `lambda` keyword.

```python
# Example
square = lambda x: x ** 2
print(square(4))
```

