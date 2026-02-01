This repository contains a full Python solution, implementing a custom Polynomial class from first principles. The project covers object-oriented programming, numerical methods, and scientific computing using NumPy, SciPy, and Matplotlib.

Key features include:

Polynomial representation using coefficient lists

Operator overloading (+, -, *)

Polynomial evaluation, differentiation, and integration

Polynomial plotting over specified intervals

Euclidean division of polynomials

Numerical verification of integrals using scipy.integrate.quad

Solving and verifying an ordinary differential equation using odeint

The code demonstrates correctness through assertions, numerical convergence checks, and graphical verification against analytical and numerical solutions.

Notes (this is old academic work):
Conditional check in 1i would help - use .’lower_bound is None or upper_bound is None’ instead.
In Q2, the result of quad is a tuple containing the integral value and an estimate of the absolute error. Comparing
only the integral values would be better.
1f:
The degree of the product of two polynomials should be equal to the sum of their individual degrees
Polynomial multiplication does not yield correct results
1i:
Polynomial class causes errors when trying to call the integral method.
2:
The testPolynomialIntegralValues function causes errors.
