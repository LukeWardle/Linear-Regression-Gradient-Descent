# Linear Regression with Gradient Descent

Practice notebook, February 2025. Implements gradient descent from scratch to fit a
linear model, and looks at what the learning rate and iteration count do to convergence.

## What it covers

- **Gradient descent written out directly** — iterative parameter updates minimising mean
  squared error, rather than calling a solver
- **Learning rate and iteration count varied**, to see the effect on whether and how fast
  the model converges
- **Cost plotted against iteration**, so the optimisation is visible rather than assumed

## Running it

```bash
pip install numpy pandas matplotlib jupyter
jupyter notebook
```

Open the notebook and run the cells in order.

## Scope

A learning exercise, not a library. The maths is written out step by step rather than
optimised, and there are no tests.

Later work in this account covers the same ground with a production structure —
[week3-linear-solvers](https://github.com/LukeWardle/week3-linear-solvers) for solver
selection and conditioning, and
[ftse-portfolio-rebalancer](https://github.com/LukeWardle/ftse-portfolio-rebalancer) for
ridge regularisation with a cross-validated penalty.
