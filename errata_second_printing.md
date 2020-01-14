# Errata (second edition second printing)
The page numbers indicated between parentheses correspond to the printed version

## Chapter 3

page 121 (---):

- equation 3.17, the sum should run from i = 1 to m (not n)

## Chapter 7

page 254 (---):

- last paragraph:
    + For the purpose of our discussion, we are going to say that a kernel is basically a symmetric
    function that takes two inputs and returns a value of [zero] (one) [in](if) the inputs are the same or [positive] (lower) otherwise.
    
    To clarify this. What it's important here is to have a function that return the highest posible value when two inputs are the same and decrease when they are not the same. As explained later Kernels for Gaussian processes are restricted to guarantee the resulting covariance matrix is positive definite.

page 261 (---):

- code block for model_reg
    + the last line is missing: `trace_reg = pm.sample(2000)`

page 266 (---):

- the code line `x_data = [islands.lat.values[:, None], islands.lon.values[:, None]]` can be removed as the variable `xdata` is not used in this example.
