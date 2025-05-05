# Useful Libraries

## Overview
Python offers numerous libraries to simplify complex tasks.

### Topics Covered

1. NumPy
2. Pandas
3. Matplotlib
4. Requests
5. Flask

### NumPy
NumPy is used for numerical computations.

```python
# Example
import numpy as np
arr = np.array([1, 2, 3])
print(arr.mean())
```

### Pandas
Pandas is used for data analysis and manipulation.

```python
# Example
import pandas as pd
data = {"Name": ["Alice", "Bob"], "Age": [25, 30]}
df = pd.DataFrame(data)
print(df)
```

### Matplotlib
Matplotlib is used for creating visualizations.

```python
# Example
import matplotlib.pyplot as plt
plt.plot([1, 2, 3], [4, 5, 6])
plt.show()
```

### Requests
Requests is used for handling HTTP requests.

```python
# Example
import requests
response = requests.get("https://api.github.com")
print(response.json())
```

### Flask
Flask is a web framework for building web applications.

```python
# Example
from flask import Flask
app = Flask(__name__)

@app.route("/")
def home():
    return "Hello, Flask!"

app.run()
```
