# tempconvert

A lightweight Python package that converts temperatures between Celsius and Fahrenheit.  
This package was created as part of the UBC MDS DSCI 524: Collaborative Software Development course.

## Features

The package currently provides the following function(s):

- `celsius_to_fahrenheit(c)`  
  Converts a temperature in Celsius to Fahrenheit using the formula `F = C × 9/5 + 32`.

## Installation

### Install from TestPyPI (recommended for this assignment)

```bash
python -m pip install --index-url https://test.pypi.org/simple --no-deps tempconvert-spanorti
```

## Usage

```python
from tempconvert.example import celsius_to_fahrenheit

print(celsius_to_fahrenheit(0))    # 32.0
print(celsius_to_fahrenheit(100))  # 212.0
```