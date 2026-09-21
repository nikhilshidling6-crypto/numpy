# NumPy Fundamentals and Array Operations

This repository contains introductory code demonstrating core operations and functionalities of the NumPy library, a fundamental package for scientific computing in Python.

## Overview

The notebook covers essential NumPy concepts, ranging from basic array creation and inspection to element-wise operations, indexing, reshaping, and matrix multiplication.

---

## Key Features & Code Examples

### 1. Array Creation & Data Types
Creating standard NumPy arrays and inspecting array properties such as data type (`dtype`) and shape (`shape`).

```python
import numpy as np

# Basic array creation
narray = np.array([1, 2, 3, 4, 5])

# Explicit data type definition
array1 = np.array([3, 4, 5, 6], dtype="int8")

# Array properties
print(type(array1)) # Output: <class 'numpy.ndarray'>
print(array1.shape) # Output: (4,)
