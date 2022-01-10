# UofT STA410/2102 Statistical Computation

## Submitting Programming Portfolio Assignments
Submit .ipynb to [MarkUs](https://markus-ds.teach.cs.toronto.edu/) before the end of the calendar day (EoD) on the due date.

## Accessing Programming Portfolio Assignments

UofT students may access STA410 Programming Portfolio Assignment coding problems with the [UofT JupyterHub](https://jupyter.utoronto.ca)
or [google colab](http://colab.research.google.com) via

> `https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https://github.com/pointOfive/STA140_HW<#>&branch=<master|main>`
> 
> or
>
> `https://colab.research.google.com/github/pointOfive/sta410hw0/blob/<master|main>/sta410hw<#>.ipynb`
>
> where `<#>` above is replaced with the Programming Portfolio Assignment number and <master|main> is replaced by `master` for `hw0` and `hw1` and `main` for all others.

Some notes to faciltate getting started in this environment are available on the UofT JupyterHub [support page](https://act.utoronto.ca/jupyterhub-support/).
If for some reason JupyterHub is not loading the repository, you can delete and reload repositories (after downloading and saving what you need).
> From JupyterHub, open a new terminal with `New` > `Terminal` and then use `yes y | rm -r <path to directory to delete>` to a delete the repository directory.


## Programming Portfolio Assignments

0. [Assignment 0](https://github.com/pointOfive/sta410hw0#uoft-sta4102102-statistical-computation) 
introduces Python through the following foundational computational and statistical computation problems:

    1. Bit string representation of integer value numbers
    2. Pseudorandom integer generation with modulus
    3. Floating-point error accumulation reduction
    4. High precision single pass variance calculations

1. [Assignment 1](https://github.com/pointOfive/sta410hw1#uoft-sta4102102-statistical-computation) 
practices linear algebra computations with numpy through the following foundational computational and statistical computation problems:

    1. The Gram-Schmidt to orthogonalize vectors
    2. Regression fits from a X=QR decomposition
    3. The Cholesky covariance matrix decomposition
    4. Conjugate gradient methods

2. [Assignment 2](https://github.com/pointOfive/sta410hw2#uoft-sta4102102-statistical-computation) 
explores the quintessential algorithms underlying the computational efficiency of the following standard use cases for function:

    1. Interpolation with Lagrange piecewise polynomials
    2. Covolution theorem with the fast Fourier transform
    3. Orthogonal polynomial recurrence formula evaluation
    4. Time-benchmarking commonly used built-in functions
