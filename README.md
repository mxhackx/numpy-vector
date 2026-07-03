# Vector

A lightweight Python library for n-dimensional vector mathematics with full operator overloading and linear algebra utilities.

## Features

- N-dimensional vector support
- Arithmetic operators: `+`, `-`, `*`, `/`, `**`, `//`, `%`
- Dot product, norm, distance
- Cross product (3D only)
- Normalization and projection
- Hadamard product and element-wise division
- Angle and cosine between vectors
- Reflection over a normal vector
- Indexing, iteration, and Pythonic behavior
- Strict type checking with custom `VectorError`

## Example

```python
from vector import Vector

v1 = Vector([1, 2, 3])
v2 = Vector([4, 5, 6])

print(v1 + v2)
print(v1.dot(v2))
print(v1.norm())
print(v1.normalize())
print(v1.cross(v2))