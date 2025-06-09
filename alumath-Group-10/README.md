# 🤖 Matrix Multiplier with Personality

This Python module provides a fun and quirky interface for performing matrix multiplication. If the matrices are incompatible, the module doesn’t just crash — it *explains why* in a clear and human-friendly way, with helpful debugging tips.

---

## 📦 Features

- Object-oriented `Matrix` class.
- Handles valid matrix multiplication.
- Detects dimension mismatches and raises detailed, non-boring errors.
- Easy to use with raw lists or `Matrix` objects.
- Custom exception: `MatrixMultiplicationError`.

---

## 🛠️ Setup

### Requirements
- Python 3.7 or newer (no external libraries required)

### Installation

Clone this repo or download the files:

```bash
git clone https://github.com/Makito042/alu-pca-ml.git
cd alu-pca-ml/alumath_group10
```

# 🚀 Usage
## Importing and creating matrices

```bash
from matrix_module import create_matrix, multiply_matrices

A = create_matrix([
    [1, 2],
    [3, 4]
])

B = create_matrix([
    [5, 6],
    [7, 8]
])

result = multiply_matrices(A, B)
print("Result:")
print(result)
```

# 🧪 Testing
Run the test script to verify functionality:

```bash
python main.py
```