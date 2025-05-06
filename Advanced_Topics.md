# Advanced Topics

## Overview
Explore advanced concepts to enhance your Python skills.

### 📌 Topics Covered

1. Generators
2. Decorators
3. Context Managers
4. Multithreading

### Generators
Generators produce items one at a time using `yield`.

```python
# Example
def count_up_to(n):
    count = 1
    while count <= n:
        yield count
        count += 1

for number in count_up_to(5):
    print(number)
```

### Decorators
Decorators modify the behavior of functions.

```python
# Example
def decorator(func):
    def wrapper():
        print("Before function call")
        func()
        print("After function call")
    return wrapper

@decorator
def say_hello():
    print("Hello!")

say_hello()
```

### Context Managers
Context managers handle resource management using `with`.

```python
# Example
with open("file.txt", "r") as file:
    content = file.read()
    print(content)
```

### Multithreading
Multithreading allows concurrent execution of tasks.

```python
# Example
import threading

def print_numbers():
    for i in range(5):
        print(i)

thread = threading.Thread(target=print_numbers)
thread.start()
thread.join()
```

