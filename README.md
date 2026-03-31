# MAT403 – Bisection Method

A Jupyter Notebook implementing the **Bisection Method** applied to a game performance optimization problem.

## Problem
Find the optimal graphics quality setting `p` (0–100) such that the game runs at exactly **60 FPS**, given the measured FPS model:

```
FPS(p) = 120.0 - 0.1109 * p^1.4776
```

## Method
The `bisection_method()` function iteratively narrows the interval `[a, b]` until `|f(m)| < tolerance`.

## Result
- **Optimal quality setting:** `p* ≈ 70.7` out of 100  
- **FPS at p*:** ~60.07  
- **Converged in:** 8 iterations  
- **Theoretical bound:** 9 iterations

## Usage
Open `MAT403.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter and run all cells.

## Requirements
- Python 3
- `math` (standard library only — no extra installs needed)
