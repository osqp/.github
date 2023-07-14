# OSQP - The Operator Splitting QP Solver

OSQP is an optimization solver for Quadratic Programs (QPs) that uses the Alternating Direction Method of Multipliers (ADMM).
It is written in pure C, and can be compiled into a library-free embedded solver for control and robotics applications.
Interfaces to high-level languages like Python, Julia, Matlab and R are also available, and OSQP can be used from
modelling languages such as CVXPY, JuMP, and YALMIP.

For more information, please see the [OSQP website](https://osqp.org).

If you use OSQP in an academic work, please cite the relevant [papers](https://osqp.org/citing/).

## Installing

### C

The OSQP C code can be found in the main [OSQP repository](https://github.com/osqp/osqp), and build instructions
can be found in the documentation.

### Python

OSQP is available through pip by doing:
```
pip install osqp
```

### Julia

OSQP is available in the general registry by running:
```
pkg> add OSQP
```

