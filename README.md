# Polynomial-Class-Numerical-Methods

This repository contains a **full Python solution implementing a custom Polynomial class from first principles**.

The project was developed as part of early academic work and focuses on **object-oriented programming**, **numerical methods**, and **scientific computing** using NumPy, SciPy, and Matplotlib. The aim was to build polynomial functionality manually rather than relying on existing symbolic or numerical libraries.

---

## Overview

The Polynomial class represents polynomials using coefficient lists and supports arithmetic operations, evaluation, calculus operations, plotting, and numerical verification.

The code also includes numerical integration checks and the solution and verification of an ordinary differential equation using SciPy, with results compared against analytical and numerical references.

Correctness is demonstrated through assertions, numerical convergence checks, and graphical comparison of results.

---

## Functionality

The implementation includes polynomial representation via coefficient lists, operator overloading for addition, subtraction, and multiplication, polynomial evaluation for scalar and array inputs, differentiation and integration, polynomial plotting over specified intervals, and Euclidean division of polynomials.

Numerical integration is verified using `scipy.integrate.quad`, and an ordinary differential equation is solved and verified using `odeint`, with graphical comparison of solutions.

---

## Verification and Validation

Assertions are used throughout the code to enforce valid inputs and detect incorrect usage.

Numerical results are validated through convergence checks, comparison against analytical expectations, and visual verification using plotted outputs.

---

## Notes (Old Academic Work)

This code reflects **early-stage academic development** and contains known limitations that are documented for transparency.

The conditional check in Part 1i would be more robust using  
`lower_bound is None or upper_bound is None`.

In Question 2, the result returned by `quad` is a tuple containing both the integral value and an error estimate; comparing only the integral values would be more appropriate.

Polynomial multiplication in Part 1f does not produce correct results, as the degree of the product should equal the sum of the individual degrees.

The `integral` method in Part 1i can raise errors when called in certain cases.

The `testPolynomialIntegralValues` function in Question 2 also produces errors and requires correction.

These issues are intentionally left visible as part of the academic record and learning process.

---

## Context

This repository is kept public as a **historical academic reference** and should not be treated as a production-ready numerical library.
