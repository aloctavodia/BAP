# Errata (second edition second printing)
The page numbers indicated between parentheses correspond to the printed version

## Chapter 3

page 121 (123):

- equation 3.17, the sum should run from i = 1 to m (not n)

## Chapter 5

page 185 (187):

- equation 5.1: $p(  T_{sim} > T_{obs} | y)$


page 193 (195):

- equation 5.5: the term $pAIC$ should be $p_{AIC}$

page 213 (215):

- equation 5.14:The sumation in the firt term should run up to $S$ not $s$   $WAIC = \displaystyle{-2 \sum_i^n \log \left(\frac{1}{S} \sum_{s=1}^S p(y_i \mid \theta^s) \right) + 2 \sum_i^n  \left( \mathop{V}_{s=1}^S \log p(y_i \mid \theta^s) \right)}$


page 218 (220):

- equation 5.18: The signs in the second line are inverted. It should be $-\sum_i p_i \log qi + \sum_i p_i \log ri$


## Chapter 7

page 254 (257):

- last paragraph:
    + For the purpose of our discussion, we are going to say that a kernel is basically a symmetric
    function that takes two inputs and returns a value of [zero] (one) [in](if) the inputs are the same or [positive] (lower) otherwise.
    
    To clarify this. What it's important here is to have a function that return the highest posible value when two inputs are the same and decrease when they are not the same. As explained later Kernels for Gaussian processes are restricted to guarantee the resulting covariance matrix is positive definite.

page 261 (264):

- code block for model_reg
    + the last line is missing: `trace_reg = pm.sample(2000)`

page 266 (269):

- the code line `x_data = [islands.lat.values[:, None], islands.lon.values[:, None]]` can be removed as the variable `xdata` is not used in this example.
