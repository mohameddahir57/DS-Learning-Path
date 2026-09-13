# Week 1 - Python & NumPy Refresh

## Overview
This week rebuilt core Python fundamentals through a data science lens, then introduced NumPy - the foundation almost every other data science library (Pandas, Scikit-learn, TensorFlow/PyTorch) is built on top of. By the end of the week, we went from refreshing basic data types to running a full simulated-data mini challenge using only vectorized operations, no loops.

## What We Covered

**Day 1 - Python Refresh for Data Science**
Reviewed Python's basic (primitive) types - int, float, str, bool, NoneType - and collection types - list, dict, tuple, set - including mutability, indexing/lookup style, and common methods for each. Also covered list comprehensions and lambda functions, and why data scientists work inside Jupyter/Colab notebooks instead of plain .py files.

**Day 2 - NumPy Basics**
Introduced NumPy and why it's faster than plain Python lists. Covered creating 1D, 2D, and 3D arrays, using shortcuts like `zeros()`, `ones()`, `arange()`, and `linspace()`, indexing and slicing arrays (including 2D row/column access), and understanding and changing array shape with `.reshape()`.

**Day 3 - NumPy Operations**
Covered vectorized operations (applying math to a whole array at once instead of looping), broadcasting between arrays of different shapes, aggregate functions (`sum()`, `mean()`, `std()`, `min()`, `max()`, including per-row/per-column aggregation with `axis`), and boolean masking to filter arrays based on conditions.

**Day 4 - NumPy Applied + Week 1 Mini Challenge**
Covered random number generation (`np.random`) and why setting a seed matters for reproducibility, combining/stacking arrays with `concatenate()`, `vstack()`, and `hstack()`, and the dot product / matrix multiplication basics that underpin later machine learning math. Closed the week with a mini challenge simulating 100 test scores and analyzing them using only vectorized operations.

## Files in This Folder
- `Day1 Python Refresh.pdf` / `Day1 Python Refresh.ipynb`
- `Day2 Numpy Basics.pdf` / `Day2 Numpy Basics.ipynb`
- `Day3 Numpy Operations.pdf` / `Day3 Numpy Operations.ipynb`
- `Day4 Numpy Applied.pdf` / `Day4 Numpy Applied.ipynb`

## Week 1 Checklist

- [x] Day 1 - Python Refresh (data types, list comprehensions, lambda functions)
- [x] Day 2 - NumPy Basics (arrays, indexing, slicing, reshaping)
- [x] Day 3 - NumPy Operations (vectorization, broadcasting, aggregates, boolean masking)
- [x] Day 4 - NumPy Applied + Mini Challenge (random generation, stacking, dot product)

## Skills Gained This Week
- Comfortable distinguishing basic types from collection types in Python
- Able to write list comprehensions and lambda functions instead of manual loops
- Able to create, index, slice, and reshape NumPy arrays
- Able to perform vectorized math operations without writing loops
- Able to filter data using boolean masks
- Able to generate reproducible random data and combine arrays together
- Understand the basic math (dot product / matrix multiplication) behind later ML models

**Next up: Week 2 - Pandas Mastery**
