# Bisection Method Notebook

This Jupyter notebook explains and demonstrates the **bisection method** for finding roots of nonlinear equations. It covers the mathematical background, stopping criteria, convergence, and order of convergence.

## What the Code Does

- Defines the function $f(x) = x^3 + 4x^2 - 10$. (Can be changed within the code)
- Asks the user for an interval $[a, b]$ to search for a root.
- Uses the bisection method to find a root within the interval, splitting the interval in half until the result is within a specified tolerance $\epsilon\$.
- Prints the root found and the number of iterations taken.
- Includes code to estimate the number of iterations needed for a given interval and tolerance.

## How to Use

1. Open the notebook in Jupyter.
2. Run the cells in order.
3. When prompted, enter the lower and upper bounds for the interval.
4. The notebook will display the root found, the number of iterations, and the expected number of iterations for your chosen interval and tolerance.

## Requirements

- Python 3.x
- Jupyter Notebook
- No extra packages required (uses only the standard `math` library)

---
**Note:**  
This notebook is for educational purposes and demonstrates the bisection method step by step, including mathematical explanations and code.
