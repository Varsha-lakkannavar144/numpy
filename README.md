# NumPy Fundamentals for Machine Learning

A structured reference guide covering numerical computing operations in Python using **NumPy**. This repository covers multi-dimensional array operations, type promotion, element-wise arithmetic, indexing, reshaping, and matrix dot products required for data science and machine learning pipelines.

---

## Technical Features

| Feature | Description | NumPy Implementation |
| :--- | :--- | :--- |
| **Array Initialization** | Constructing multi-dimensional `ndarray` objects. | `np.array()`, `np.zeros()` |
| **Type Promotion** | Automatic type casting when handling mixed inputs. | `dtype='<U21'` (string conversion) |
| **Vectorized Operations** | High-performance element-wise array arithmetic. | `n1 * n2` |
| **Boolean Indexing** | Conditional filtering without explicit loops. | `arr[arr > 3]` |
| **Array Reshaping** | Modifying tensor dimensions while maintaining data contiguousness[cite: 4]. | `arr.reshape(rows, cols)`[cite: 4] |
| **Linear Algebra** | Matrix multiplication operations for linear systems[cite: 4]. | `@` operator or `np.matmul()` |

---

## Environment & Dependency Setup

Ensure NumPy is installed in your runtime environment[cite: 4]:

```bash
pip install numpy
