# UofT STA410/2102 Statistical Computation


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

3. [Assignment 3](https://github.com/pointOfive/sta410hw3#uoft-sta4102102-statistical-computation) 
addresses optimization with a particular focus on Newton's Method
and TensorFlow for Gradient and Hessian (Jacobian) computations.

    1. Root-finding with Newton-Raphson and fixed-point iteration and acceleration
    2. Iteratively reweighted least squares for fitting logistic regression models
    3. Nonlinear Gauss-Seidel using TensorFlow for partial derivative calculations 
    4. Newton's method for arbitrary dimension gradients/Hessians with TensorFlow    
    
## Submitting Programming Portfolio Assignments
Submit `.ipynb` files on [MarkUs](https://markus-ds.teach.cs.toronto.edu/) before the end of the calendar day (EoD) on the due date.

## Accessing Programming Portfolio Assignments

UofT students may access STA410 Programming Portfolio Assignment coding problems with UofT JupyterHub or JupyterLab or [google colab](http://colab.research.google.com) via

> [JupyterHub] `https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https://github.com/pointOfive/sta410hw<#>&branch=<master|main>`
>
> [JupyterLab] `https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https://github.com/pointOfive/sta410hw<#>&branch=<master|main>&urlpath=/lab/tree/sta410hw<#>`
> 
> or
>
> `https://colab.research.google.com/github/pointOfive/sta410hw0/blob/<master|main>/sta410hw<#>.ipynb`
>
> where `<#>` above is replaced with the Programming Portfolio Assignment number and <master|main> is replaced by `master` for `hw0` and `hw1` and `main` for all others.

### Additional Information and Requirements

Some notes to faciltate getting started in this environment are available on the UofT JupyterHub [support page](https://act.utoronto.ca/jupyterhub-support/).

If for some reason JupyterHub/Lab is not loading the repository, you can delete and reload repositories (after downloading and saving what you need).
> From JupyterLab or JupyterHub, open a new terminal with `New` > `Terminal` and then use `yes y | rm -r <path to directory to delete>` to a delete the repository directory.

***If you're working in some other environment, 
the versioning there must support [notebook format 4.5](https://github.com/jupyterlab/jupyterlab/issues/9729), e.g., 
[JupyterLab >= 3.0.13](https://github.com/jupyterlab/jupyterlab/releases/tag/v3.0.13) (for "JupyterLab UI")
or [Jupyter Notebook >= 6.2](https://jupyter-notebook.readthedocs.io/en/stable/changelog.html#changelog) (for "Jupyter classic UI"); 
otherwise, your notebook cell-ids will not be supported and you will not get any credit for your submitted work.***

> You may check if cell ids are present or changing at each save with `! grep '"id":' <path/to/notebook>.ipynb`


