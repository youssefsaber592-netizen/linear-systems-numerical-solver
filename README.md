# Numerical Analysis Project - Linear Systems Solvers

[cite_start]Welcome to the **Numerical Analysis Project** developed for the Numerical Analysis course at **Modern Academy** (Class: **C12**)[cite: 1, 2, 3]. [cite_start]This project implements and demonstrates various direct and iterative numerical methods to solve systems of linear equations, complete with an error analysis comparison[cite: 13, 14, 57, 73, 86, 93].


---

## 👥 Team Members

* [cite_start]**Mark Nader Kamal Saad** - Code: `12500407` [cite: 5, 7]
* [cite_start]**Omar Eid Mohamed** - Code: `12500187` [cite: 6, 8]
* [cite_start]**Youssef Saber Salama Awad Elian** - Code: `12500327` [cite: 9, 10]
* [cite_start]**Ahmed Hamdy Ahmed Mahdy** - Code: `12500725` [cite: 11, 12]

---

## 📌 Methods Implemented

This project covers four major methods divided into two categories:

### [cite_start]1. Iterative Methods (Approximate Solutions) [cite: 93]
* [cite_start]**The Jacobi Method:** Solves each equation for one variable and uses the values from the previous iteration to calculate the next approximation[cite: 14, 20, 26].
* [cite_start]**The Gauss-Seidel Method:** Similar to Jacobi but utilizes the newly computed values immediately within the same iteration for faster convergence[cite: 13, 56, 57, 59, 62].

### [cite_start]2. Direct Methods (Exact Solutions) [cite: 93]
* [cite_start]**The Cramer's Rule:** Uses determinants of matrices to find exact solutions[cite: 73, 76].
* [cite_start]**The Matrix Method (Gauss-Jordan Elimination / Inversion):** Solves the system using the formula $X = A^{-1} \cdot B$ through row reduction operations[cite: 86, 88].

---

## 🧮 Mathematical Overview & Example

[cite_start]The system implemented and analyzed in this project is[cite: 31]:
[cite_start]$$8x_{1} + 2x_{2} - 3x_{3} = 21$$ [cite: 32]
[cite_start]$$-x_{1} - 10x_{2} + 4x_{3} = 13$$ [cite: 32]
[cite_start]$$2x_{1} + 3x_{2} + 9x_{3} = -15$$ [cite: 33]

### Comparison of Final Results:
* **Exact Solution (Cramer/Matrix):** $x_1 = 2.596$, $x_2 = -2.168$, $x_3 = -1.521$
* [cite_start]**Jacobi Approximation (3rd Iteration):** $x_1 \approx 2.501$, $x_2 \approx -2.259$, $x_3 \approx -1.440$ [cite: 53, 55]
* **Gauss-Seidel Approximation (3rd Iteration):** $x_1 \approx 2.638$, $x_2 \approx -2.143$, $x_3 \approx -1.538$

---

## [cite_start]📊 Error Analysis [cite: 93]

[cite_start]An explicit error analysis was conducted by measuring the difference between the **Exact** and **Approximate** solutions using Absolute Error ($E_a$) and Relative Error ($E_r$)[cite: 93]:

[cite_start]$$E_{a} = |x_{exact} - x_{approx}|$$ [cite: 93, 94]
$$E_{r} = \left| \frac{x_{exact} - x_{approx}}{x_{exact}} \right| [cite_start]\times 100\%$$ [cite: 94]

### Results Summary:
* **Gauss-Seidel** achieved a lower relative error compared to the **Jacobi method** within the same number of iterations, showcasing its superior convergence rate.

---

## 📷 Code & Output Previews

Below are the screenshots detailing the code implementation and execution results:

### Source Code Pages
| Page 1 | Page 2 |
|--- |--- |
| ![Code Page 1](project/photos/code/code_page-0001.jpg) | ![Code Page 2](project/photos/code/code_page-0002.jpg) |

| Page 3 | Page 4 |
|--- |--- |
| ![Code Page 3](project/photos/code/code_page-0003.jpg) | ![Code Page 4](project/photos/code/code_page-0004.jpg) |

| Page 5 |
|--- |
| ![Code Page 5](project/photos/code/code_page-0005.jpg) |

### Program Execution & Output
* **Terminal Output:**
![Output Page 1](project/photos/output/output_page-0001.jpg)

---

## 🚀 How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/youssefsaber592-netizen/linear-systems-numerical-solver.git](https://github.com/youssefsaber592-netizen/linear-systems-numerical-solver.git)
