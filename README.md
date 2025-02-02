# Function-Optimization
This project was made in 1st Year of Univesity in Calculus 2 course by myself and its about otimization algorithms and their application to different types of objective functions

# 🏋️ Optimization Algorithms & Linear Programming

## 📌 Overview  
This project explores **optimization algorithms**, specifically **Gradient Descent with Momentum**, and applies them to different objective functions such as **quadratic**, **cubic**, and **non-convex** functions. Additionally, a simple **Linear Programming** example is included to solve optimization problems with constraints. The goal is to visualize and experiment with different learning rates and momentum values to understand their impact on optimization.

---

## 🧑‍💻 Objective Functions  
This project works with the following objective functions:
- **Quadratic Function**: \( f(w) = 2w^2 + 4w \)  
- **Cubic Function**: \( f(w) = w^3 - 3w^2 + 2w \)  
- **Non-Convex Function**: \( f(w) = \sin(w) + 0.1w^2 \)  

Each function is optimized using **Gradient Descent with Momentum**, and various experiments are conducted to analyze the optimization behavior.

---

## 🛠️ Features & Methods  

### ✅ **1. Gradient Descent Algorithm with Momentum**  
- The algorithm iterates to minimize the objective function using gradient descent.  
- **Momentum** helps to accelerate convergence and avoid oscillations by considering past gradients.  
- Experimentation is done with various **learning rates** and **momentum values**.

### ✅ **2. Objective Function Experiments**  
For each function, experiments are conducted with the following configurations:  
- Learning Rates: **0.1, 0.5, 0.9**  
- Momentum Values: **0.1, 0.5, 0.9**  
- **Visualization**: The progress of the optimization is shown using contour plots.

### ✅ **3. Linear Programming (LP) Example**  
A simple linear programming problem is solved using **SciPy's `linprog`**:  
- Maximize: \( 3x + 4y \)  
- Subject to: \( x + y \leq 5, x \geq 0, y \geq 0 \)  

This demonstrates an optimization problem with linear constraints.

---

## 📊 Visualizations  

### 🔥 **Function Visualization**  
Visualize the optimization progress for different objective functions using contour plots with color maps. The plot shows how the gradient descent algorithm converges to the minimum.  

### 🎯 **Optimization Path**  
The path taken by the gradient descent algorithm is plotted to show the movement towards the optimal solution.

---

## 🛠️ Installation & Usage  

### **🔹 Prerequisites**  
Ensure you have **Python 3+** installed along with the following libraries:  
```sh
pip install numpy matplotlib scipy
