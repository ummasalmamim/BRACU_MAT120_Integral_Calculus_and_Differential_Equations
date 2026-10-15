# MAT120 — Integral Calculus and Differential Equations

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![SymPy](https://img.shields.io/badge/SymPy-Symbolic%20Math-3B5526)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-013243?logo=numpy)
![SciPy](https://img.shields.io/badge/SciPy-Integration%20%26%20ODEs-8CAAE6?logo=scipy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Plotting-11557C)

**BRAC University · Department of Mathematics and Natural Sciences (MNS)**

This repository contains my lab work, work, a group project and practice material for the course **MAT120: Mathematics II — Integral Calculus and Differential Equations.** The notebooks use Python to explore symbolic and numerical methods for integration and ordinary differential equations.

**Author:** [Umma Salma Mim](https://github.com/ummasalmamim)

---

## Table of Contents

- [Course Information](#course-information)
- [Course Overview](#course-overview)
- [Repository Contents](#repository-contents)
- [Topics Covered](#topics-covered)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Academic Integrity](#academic-integrity)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

---

## Course Information

| Item            | Details                                                        |
| --------------- | -------------------------------------------------------------- |
| **Institution** | BRAC University, Dhaka, Bangladesh                             |
| **Course Code** | MAT120                                                         |
| **Course Title**| Mathematics II: Integral Calculus and Differential Equations   |
| **Credits**     | 3                                                              |
| **Prerequisite**| MAT110 (Differential Calculus and Co-ordinate Geometry)        |
| **Semester**    | Summer 2023                                                    |
| **Section**     | 7                                                              |
| **Official Page** | [BRAC University — Courses Offered (MPS)](https://www.bracu.ac.bd/academics/schools-and-departments/department-mathematics-physical-sciences/courses-offered-mps) |

---

## Course Overview

According to the official BRAC University course outline, MAT120 consists of two major parts:

**Integral Calculus**
- Definitions of integration; integration by substitution, by parts, and by successive reduction
- Standard integrals; definite integrals, their properties, and their use in summing series
- Wallis's formula; improper integrals; Beta and Gamma functions
- Area under a plane curve and between two curves (Cartesian and polar coordinates)
- Numerical integration: Trapezoidal rule and Simpson's rule
- Arc length (Cartesian, polar, parametric and pedal forms); intrinsic equations
- Volumes of solids of revolution (including the shell method) and area of surfaces of revolution

**Ordinary Differential Equations**
- Order and degree of ODEs; formation of differential equations
- Solution of first-order differential equations by various methods
- Linear equations of second and higher order with constant coefficients
- Homogeneous linear equations and their applications
- Higher-order equations with absent dependent or independent variables
- Solution by factorisation of operators

The laboratory component of the course applies these concepts computationally using Python.

---

## Repository Contents

| # | Notebook | Description |
|---|----------|-------------|
| 1 | [`Lab_1_Umma Salma Mim.ipynb`](Lab_1_Umma%20Salma%20Mim.ipynb) | Introduction to SymPy: defining symbols and multivariable expressions, substitution and evaluation, complex numbers, and exact symbolic values. |
| 2 | [`Lab_2_Umma Salma Mim.ipynb`](Lab_2_Umma%20Salma%20Mim.ipynb) | Plotting functions and their derivatives using `lambdify` and Matplotlib; introduction to symbolic integration. |
| 3 | [`Lab_3_Umma_Salma_Mim.ipynb`](Lab_3_Umma_Salma_Mim.ipynb) | Trapezoidal rule for definite integrals, solving algebraic equations, and solving the first-order ODE `dy/dx = −y²/x²` with the initial condition `y(1) = 1/2`. |
| 4 | [`Lab_4_Umma_Salma_Mim.ipynb`](Lab_4_Umma_Salma_Mim.ipynb) | Further practice with the trapezoidal rule, symbolic functions and derivatives, and ODE solutions with initial conditions using `dsolve`. |
| 5 | [`Lab_5_Umma_Salma_Mim.ipynb`](Lab_5_Umma_Salma_Mim.ipynb) | Analytical solution of a first-order ODE and plotting its solution curves across domains that avoid singular points. |
| 6 | [`Umma_Salma_Mim_Quiz.ipynb`](Umma_Salma_Mim_Quiz.ipynb) | Lab quiz: symbolic differentiation, the trapezoidal rule, numerical integration with `scipy.integrate.quad`, and evaluation of the Gamma function. |
| 7 | [`Mat_120_Project_Group_G.ipynb`](Mat_120_Project_Group_G.ipynb) | **Group project — Newton's Law of Cooling.** Models `dT/dt = −k(T − Tₛ)` and solves it analytically (SymPy), numerically (`scipy.integrate.odeint`), and with Euler's method, comparing the results graphically. |

---

## Topics Covered

- Symbolic mathematics with SymPy (symbols, expressions, substitution, `solve`, `diff`, `integrate`, `dsolve`)
- Visualising functions and their derivatives
- Definite and improper integrals
- Numerical integration (Trapezoidal rule, SciPy `quad`)
- Special functions (Gamma function)
- First-order ordinary differential equations and initial value problems
- Numerical ODE solvers (`odeint`, Euler's method)
- Real-world modelling with differential equations (Newton's Law of Cooling)

---

## Technologies Used

- **Python 3**
- **Jupyter Notebook / Google Colab**
- **SymPy** — symbolic computation
- **NumPy** — numerical arrays and operations
- **SciPy** — numerical integration and ODE solving
- **Matplotlib** — plotting and visualisation

---

## Getting Started

### Option 1: Run in Google Colab (no installation required)

1. Open [Google Colab](https://colab.research.google.com/).
2. Select **File → Open notebook → GitHub**.
3. Paste this repository's URL:
   `https://github.com/ummasalmamim/BRACU_MAT120_Integral_Calculus_and_Differential_Equations`
4. Choose a notebook and run the cells in order (**Runtime → Run all**).

### Option 2: Run locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/ummasalmamim/BRACU_MAT120_Integral_Calculus_and_Differential_Equations.git
   cd BRACU_MAT120_Integral_Calculus_and_Differential_Equations
   ```

2. **(Optional) Create a virtual environment**
   ```bash
   python -m venv venv
   # Windows
   venv\Scripts\activate
   # macOS / Linux
   source venv/bin/activate
   ```

3. **Install the dependencies**
   ```bash
   pip install notebook sympy numpy scipy matplotlib
   ```

4. **Launch Jupyter**
   ```bash
   jupyter notebook
   ```

5. Open any `.ipynb` file in the browser and run the cells from top to bottom.

---

## Repository Structure

```
BRACU_MAT120_Integral_Calculus_and_Differential_Equations/
├── Lab_1_Umma Salma Mim.ipynb
├── Lab_2_Umma Salma Mim.ipynb
├── Lab_3_Umma_Salma_Mim.ipynb
├── Lab_4_Umma_Salma_Mim.ipynb
├── Lab_5_Umma_Salma_Mim.ipynb
├── Mat_120_Project_Group_G.ipynb
├── Umma_Salma_Mim_Quiz.ipynb
└── README.md
```

---

## Academic Integrity

This repository is shared for **learning and reference purposes only**. Students currently enrolled in MAT120 are encouraged to use it to understand concepts, not to copy solutions. Please follow BRAC University's academic integrity policy and submit only your own work.

---

## Author

**Umma Salma Mim**
Undergraduate Student, BRAC University
GitHub: [@ummasalmamim](https://github.com/ummasalmamim)

**Group Project (Group G) collaborator:** Faishal Monir
GitHub: [@faishalmonir](https://github.com/Faishal-Monir)

---

## Acknowledgements

- Department of Mathematics and Natural Sciences, BRAC University, for the course design and laboratory guidance
- Course instructors and lab faculty of MAT120, Summer 2023
- The open-source developers of SymPy, NumPy, SciPy, Matplotlib, and Jupyter

---

<p align="center"><i>If you find this repository helpful, consider giving it a ⭐</i></p>
