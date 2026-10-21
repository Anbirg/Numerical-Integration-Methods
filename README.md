# Numerical Integration Methods

Educational project demonstrating numerical integration techniques implemented in Python. The project compares custom numerical approximation methods with high-precision library benchmarks.

## Features
* **Midpoint Rule** (Метод средних прямоугольников) with automatic precision tuning.
* **Trapezoidal Rule** (Метод трапеций) with automatic precision tuning.
* **Scipy Quad Integration** (`scipy.integrate.quad`) used as a high-precision reference baseline.
* **Visualization** using `matplotlib` to plot the target function and illustrate the geometric approximations.

## Requirements
* Python 3.x
* `numpy`
* `matplotlib`
* `scipy`

Install dependencies via pip:
```bash
pip install numpy matplotlib scipy

Project Structurenumerical_integration.py — Main Python script containing the algorithms and visualization.Копия_блокнота__Інтегрування_ipynb_.ipynb — Original Jupyter Notebook version.requirements.txt — Project dependencies file.UsageRun the script to execute the calculations, output the results for $\varepsilon = 10^{-4}$, and generate the comparison plot:
