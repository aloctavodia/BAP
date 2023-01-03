# Bayesian Analysis with Python (Second edition)

This is the code repository for [Bayesian Analysis with Python](https://www.packtpub.com/big-data-and-business-intelligence/bayesian-analysis-python-second-edition), published by Packt. It contains all the code necessary to work through the book from start to finish. You can find the code from the first edition in the folder `first_edition`

## Feedback

If you have read Bayesian Analysis with Python (second edition). I will really appreciate if you can answer this very brief [questionnaire](https://forms.gle/8wbUttTUHg3kwLHc8)


## Installation

The code in the book was written using Python version 3.6. To install Python and Python libraries, I recommend using Anaconda, a scientific computing distribution. You can read more about Anaconda and download it at https:/​ / ​ www.​ anaconda.​ com/​ download/​ . This will install many useful Python packages on you system. You will need to install two more packages. To install PyMC3 please use conda :


```
conda install -c conda-forge pymc3
```

And for ArviZ you can do it with the following command:

```
pip install arviz
```

An alternative way to install the necessary packages, once Anaconda is installed in your system, is to go to https://github.com/aloctavodia/BAP and download the environment file named `bap.yml`. Using it, you can install all the necessary packages by doing:

```
conda env create -f bap.yml
```

For your reference the book was writting using the following python packages:

* Ipython 7.0
* Jupyter 1.0 (or Jupyter-lab 0.35)
* NumPy 1.14.2
* SciPy 1.1
* Pandas  0.23.4
* Matplotlib 3.0.2
* Seaborn 0.9.0
* ArviZ 0.3.1
* PyMC3 3.6


## Errata

If you find an error in the book please fill an issue or send a pull request. Please before reporting an error read the `errata.md` file and verify the error has not being reported before.


## Changes from first edition

I have tried to incorporate all comments and critics from the first edition as well as much as possible input from students that have taken Bayesian courses with me. I have tried to remove those sections that I consider not very useful from the first edition and focus on improving and sometimes expanding those that contribute to understanding the basic elements of the Bayesian Analysis. I have added some new exercises and I try to provide useful summaries at the end of the book, I realized the ones from the first edition were almost useless. 

The code in the book has being updated to better reflect the new features of PyMC3. While the first edition was based on PyMC 3.0, the second edition uses PyMC 3.6. The books also relies on the new Python Library [ArviZ](https://arviz-devs.github.io/arviz/) (version 0.3.1) for summaries, diagnostics and most of the plots. 


This is a list of the most important differences per chapter.

* Chapter 1: Thinking Probabilistically. The Chapter have been updated to ease the introduction of the basic concepts of probability and Bayesian statistics and its implications for data analysis.

* Chapter 2: Programming Probabilistically. Chapter 2 and 3 from first edition have been unified and revised. This is now a more solid chapter setting the fundamentals of Bayesian statistics and probabilistic programming. New examples have been added.

* Chapter 3: Modeling with Linear Regression. A new procedure to compute the R² score is explained. I have added a new example about performing linear regression with variable variance and using shared variables.

* Chapter 4. Generalizing Linear Models. Content that was previously part of the mixture model chapter has been moved here providing a more coherent description of GLM models.

* Chapter 5. Model comparison. The content has been revised. I have added a discussion of Bayesian p-values. A brief discussion of the entropy, KL divergence and it relation to WAIC and model averaging. A new example showing how to compute Bayes Factors with Sequential Monte Carlo is shown

* Chapter 6 Mixture models. This chapter have been rewritten from scratch. The focus in on the basic elements of finite and infinite (Gaussian) mixture models. 

* Chapter 7 Gaussian process. This chapter have been rewritten from scratch. I am particularly happy with this chapter. New examples are used to intuitively explain what GP are before applying them. The chapter uses the GP module that is part of PyMC3. The new examples include regression, classification and Cox processes.

* Chapter 8 Inference engine. The discussion of numerical methods to approximate the posterior and how to diagnose samples has its own chapter now. An explanation of how Sequential Monte Carlo works is also included. Although the chapter (and book) is focused on Markov Chain Monte Carlo methods, there is also a brief discussion about Variational Methods.

* Chapter 9, Where To Go Next?, provides a list of resources for you to keep learning from beyond this book, and a very short _farewell speech_.


The main aim from the first edition remains. That is, to help people with some Python experience but with no previous statistical knowledge to get started with Bayesian data analysis and probabilistic programming.
