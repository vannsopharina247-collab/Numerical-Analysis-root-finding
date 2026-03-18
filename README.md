# Numerical-Analysis-root-finding
# Project description
This project implements a RootFindingProblem class for solving equations of the form:

[ f(x) = 0 ]

using classical numerical methods written manually in Python.
# Implemented methods
- Bisection Method
- Fixed-point Iteration
- Newton's Method
- Secant Method
- False Position Method (Regular Falsi)
- Horner's Method
- Muller's Method
- Steffensen's Method (included because it appears in the required class structure)
# How the project solve the assignment
solve(method, **kwargs)
# The solve() method internally dispatches to private methods:

- _bisection(...)
- _fixed_point(...)
- _newton(...)
- _secant(...)
- _false_position(...)
- _steffensen(...)
- _horner(coeffs, x)
- _muller(...)
This follows the assignment structure.
# File Structure
root-finding-project/
│── root_finding.py
│── examples.py
│── README.md
