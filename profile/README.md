# OSQP - The Operator Splitting QP Solver

![PyPI - downloads](https://img.shields.io/pypi/dm/osqp.svg?label=Pypi%20downloads)
![Conda - downloads](https://img.shields.io/conda/dn/conda-forge/osqp.svg?label=Conda%20downloads)
![Julia - downloads](https://img.shields.io/endpoint?url=https%3A%2F%2Fpkgs.genieframework.com%2Fapi%2Fv1%2Fbadge%2FOSQP&label=Julia%20downloads)

OSQP is an optimization solver for Quadratic Programs (QPs) that uses the Alternating Direction Method of Multipliers (ADMM).
It is written in pure C, and can be compiled into a library-free embedded solver for control and robotics applications.
Interfaces to high-level languages like Python, Julia, Matlab and R are also available, and OSQP can be used from
modelling languages such as CVXPY, JuMP, and YALMIP.

[**Visit the documentation**](https://osqp.org/docs/) to learn how to use OSQP.

[**Visit our GitHub Discussions page**](https://github.com/orgs/osqp/discussions) for any questions related to the solver!

If you use OSQP in an academic work, please cite the relevant [papers](https://osqp.org/citing/).

For more information, please see the [OSQP website](https://osqp.org).

## Installing

### C

The OSQP C code can be found in the main [OSQP repository](https://github.com/osqp/osqp), and build instructions
can be found in the documentation.

### Python

OSQP is available through [PyPI](https://pypi.org/project/osqp/) by doing:
```
pip install osqp
```

OSQP is also available from [Conda forge](https://anaconda.org/conda-forge/osqp) by doing:
```
conda install -c conda-forge osqp
```


### Julia

OSQP is available in the [general registry](https://juliahub.com/ui/Packages/OSQP/BVtcb) by running:
```
pkg> add OSQP
```

