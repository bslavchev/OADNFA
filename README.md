# OADNFA
One Algorithm Does Not Fit All - a Machine Learning-based meta-solver for the treewidth problem

## Introduction

Multiple good treewidth solvers exist, and while some are better "on average" than others, that is clearly not the best way to select which solver to execute. As we demonstrated in our [2019 paper](https://www.mdpi.com/1999-4893/12/10/200), even a rudimentary Machine Learning algorithm selection approach can dramatically improve performance by selecting a solver from a portfolio for each problem instance on an online case-by-case basis.

OADNFA is our practical implementation of the algorithm proposed in our paper.

## Roadmap

- [x] Containerize treewidth solvers (available [here](https://github.com/containerized-PACE/treewidth)).
- [ ] Write a critical review report of thesis project
- [ ] Re-develop ML model, taking findings of critical review into account
- [ ] Develop dispatcher script that allows the ML model to execute the solvers
- [ ] Containerize ML model + dispatcher script + solvers

## Wishlist
These are roadmap items that have not found a place on the roadmap yet.
- optimize Docker containers for size
-
