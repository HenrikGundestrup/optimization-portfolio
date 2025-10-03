# Gradient Descent on Rosenbrock’s Function

## 📌 Problem
The **Rosenbrock function** is a classic non-convex test function for optimization algorithms:

$$
f(x, y) = (a - x)^2 + b(y - x^2)^2, \quad a = 1, \, b = 100
$$

It has a global minimum at $(x, y) = (1, 1)$, but the narrow, curved valley makes it challenging for basic optimization methods.  
The goal of this project is to apply **Gradient Descent (GD)** and analyze its convergence behavior.

## ⚙️ Method
- Implemented **Gradient Descent from scratch** in Python.
- Explored different approaches:
  - Constant learning rate
  - Adaptive step size (line search)
  - Momentum and Nesterov acceleration
- Tracked convergence by plotting the function value over iterations and visualizing the optimization path on the function’s contour plot.

## 📊 Results
- Basic Gradient Descent converges slowly and can oscillate near the valley.
- Momentum and Nesterov acceleration significantly improve convergence speed.
- Plots show the optimization trajectory approaching the global minimum at $(1, 1)$.

**Included visualizations:**
- Loss vs. iterations
- Optimization path on contour plot

## 🧩 Files
- `gradient_descent_rosenbrock.ipynb` → Python notebook with implementation and plots
- `README.md` → this description

