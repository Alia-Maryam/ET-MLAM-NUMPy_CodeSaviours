# ET-MLAM-NUMPy_CodeSaviours
🔢 Complete NumPy Practice Notebook

A beginner-friendly, teacher-style NumPy practice notebook with heavily commented examples, practice exercises, worked solutions, and a final challenge.

The notebook is designed to explain not only how to use NumPy, but also why each feature is useful.

📘 Notebook

Notebook: numpy_full_course_solved.ipynb

Language: Python

Notebook format: Jupyter Notebook (nbformat 4)

Python version recorded in the notebook: 3.12.3

NumPy version recorded in the notebook: 2.4.4

🎯 What You'll Learn

The notebook covers the following NumPy fundamentals:

Why NumPy exists and why vectorized operations are useful

Creating NumPy arrays

Array properties such as shape, ndim, size, and dtype

Indexing and slicing

Boolean indexing and fancy indexing

Vectorized mathematical operations

Aggregation functions and the axis parameter

Reshaping, flattening, and transposing arrays

Broadcasting

Linear algebra essentials

Utility functions such as sort, where, and unique

A final challenge combining the concepts from the course

🗂️ Course Structure

0. Why Does NumPy Exist?

Introduces the motivation behind NumPy and compares Python-list operations with NumPy array operations.

Topics include:

ndarray

Performance and memory efficiency

Vectorization

Basic NumPy setup and version checking

1. Creating Arrays

Learn different ways to create arrays:

np.array()

np.zeros()

np.ones()

np.full()

np.arange()

np.linspace()

np.eye()

np.random.rand()

np.random.randint()

Reproducible randomness with np.random.seed()

Includes Practice Exercise 1 with a complete solution.

2. Array Properties — Knowing Your Data

Learn how to inspect an array using:

.shape

.ndim

.size

.dtype

.itemsize

.astype()

Includes Practice Exercise 2 with a complete solution.

3. Indexing & Slicing

Covers:

Basic indexing

Negative indexing

Slicing

Step-based slicing

Reversing arrays

2D row and column selection

Sub-matrix selection

Boolean indexing

Fancy indexing

Includes Practice Exercise 3 with a complete solution.

4. Vectorized Math Operations

Learn how to perform calculations on entire arrays without explicit loops.

Topics include:

Element-wise addition

Subtraction

Multiplication

Division

Powers

Scalar operations

np.sqrt()

np.exp()

np.log()

np.abs()

np.round()

Includes Practice Exercise 4 with a complete solution.

5. Aggregation Functions

Learn how to summarize data using:

np.sum()

np.mean()

np.median()

np.std()

np.var()

np.min()

np.max()

np.argmax()

np.argmin()

Also introduces aggregation along different axes:

axis=0

axis=1

Includes an important explanation of how axis works and Practice Exercise 5 with a complete solution.

6. Reshaping Arrays

Covers:

.reshape()

Automatic dimension inference with -1

.flatten()

.T / transpose

Includes Practice Exercise 6 with a complete solution.

7. Broadcasting

Explains how NumPy performs operations between arrays with compatible but different shapes.

Topics include:

Broadcasting with scalars

Broadcasting a 1D array across a matrix

Broadcasting compatibility rules

Recognizing broadcasting errors

Includes examples of both successful broadcasting and an expected ValueError.

Includes Practice Exercise 7 with a complete solution.

8. Linear Algebra Essentials

Introduces basic matrix operations:

Element-wise multiplication with *

Matrix multiplication with @

np.dot()

np.linalg.det()

np.linalg.inv()

Includes Practice Exercise 8 with a complete solution.

9. Useful Utility Functions

Covers common functions for practical data work:

np.sort()

np.where()

np.unique()

return_counts=True

Includes Practice Exercise 9 with a complete solution.

🏆 Final Challenge

The notebook finishes with a temperature-analysis challenge using 72 hourly temperature readings across 3 days.

The challenge combines:

Random array generation

Reshaping

Aggregation with axis

Finding the maximum with np.argmax()

Converting a flat index with np.unravel_index()

Vectorized Celsius-to-Fahrenheit conversion

Conditional labeling with np.where()

The challenge solution is included in the notebook.

📝 Practice-Based Learning

Each major section contains a Practice Exercise followed by a worked solution.

The intended learning workflow is:

Read the explanation.

Run the example cells.

Attempt the practice exercise yourself.

Compare your solution with the provided solution.

Experiment by changing the examples.

The notebook is written with comments explaining the purpose of operations rather than only showing syntax.

🚀 Getting Started

1. Install Python

Use Python 3.12 or another compatible Python environment.

2. Install NumPy and Jupyter

pip install numpy jupyter

3. Start Jupyter Notebook

jupyter notebook

4. Open the Notebook

Open:

numpy_full_course_solved.ipynb

5. Run Cells in Order

The notebook recommends running cells sequentially using:

Shift + Enter

This is important because later examples may build on variables introduced earlier.

📦 Main Dependency

The notebook primarily uses:

import numpy as np

It also uses Python's built-in time module in the introductory performance comparison.

💡 Recommended Learning Approach

Don't just read the solutions.

For each exercise:

First solve it without looking at the answer.

Change the numbers and array shapes.

Intentionally create shape mismatches to understand errors.

Try both the NumPy solution and a Python-loop equivalent where appropriate.

Pay particular attention to shape, axis, indexing, and broadcasting.

These concepts appear repeatedly in practical NumPy and data-science work.

🔗 Useful NumPy Reference

The official NumPy documentation is useful for going beyond the examples in this notebook:

NumPy documentation: https://numpy.org/doc/stable/

NumPy Quickstart: https://numpy.org/doc/stable/user/quickstart.html

Broadcasting: https://numpy.org/doc/stable/user/basics.broadcasting.html

Indexing: https://numpy.org/doc/stable/user/basics.indexing.html

📈 Next Steps

The notebook itself recommends continuing with:

Pandas, which is built around NumPy concepts.

NumPy random distributions.

NumPy's role in machine-learning libraries.

Made for learning NumPy through explanation, practice, and repetition. ❤️
