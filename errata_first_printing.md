# Errata (second edition first printing)
The page numbers indicated between parentheses correspond to the printed version

## Chapter 2

page 43 (44):

expresion 2.1 should be

$$\theta \sim Beta(\alpha, \beta)$$
$$y \sim Bern(p=\theta)$$

or equivalently 

$$\theta \sim Beta(\alpha, \beta)$$
$$y \sim Binom(n=1, p=\theta)$$

page 50 (51):

- As we can see, the result looks somewhat similar for lossf_a is $\hat \theta = 0.32$

page 53 (54):

- As I am not a [not a] ethologist [...]

page 59 (60):

- second paragraph: "I(t')s the theoretical distribution [...]"
- last paragraph, third sentence: replace "for $\nu > 2$" with "for $\nu <= 2$" 

page 63 (64):

- second paragraph: "how a few of the predictive samples look[s] very flat." 

page 64 (65):

- first paragraph: "to the value[s] estimated"

page 65 (66):

- second paragraph: "help their kids grow[n] stronger"

page 66 (67):

- the pooled standard deviation should have a plus (+) instead of a minus (-) sign between the group standard deviations. That is:
     $$\frac{\mu_2 - \mu_1}{\sqrt{\frac{{\sigma_2}^2 + {\sigma_1}^2}{2}}}$$

page 73 (74):

- first paragraph: "i(t')s also possible"

page 74 (75):

- first bullet point: "We have [have] defined two [...]"

page 83 (84):

- first paragraph: "And that is, ladies, gentlem[a] (e) n"


## Chapter 3

page 95 (97):

- first paragraph: "this constrain(t) is relaxed"

page 100 (102):

- second to last paragraph: "interval [-1, 1][. It does not matter about](, regardless of) the scale of the data."
- last paragraph: "how much y change(s)"

page 109 (111):

- code block, 4th and 3rd line from bottom: f-strings missing the "f".

page 116 (118):

- first paragraph: "with an[d] increasing amount"

page 119 (121):

- second paragraph: "They are just (k)nobs"

page 120 (122):

- first paragraph: "Well that's the subject of Chapter [6] (5), Model Comparison"

page 121 (123):

Here, $\beta$ is a  vector of coefficients of length $m$, that is, the number of (in)dependent variables.

page 128 (130):

- first paragraph: "Using a fo(rest plot)"

- Figure 3.22 have been updated

page 133 (135):

- Figure 3.26 have been updated

page 135 (137):

- In all of the examples we have seen so far, the (in)dependent variables contribute additively to the predicted variable.

page 136 (138):

- For those cases, we may want to consider the variance as a (linear) function of the (in)dependent variable.

Page 141 (143):

- Exercise 6: "ArviZ functions like plot_trace and plot_pair"

Page 142 (144):

- Exercise 14: This time (a)dd uncertainy to the linear plot
- Exercise 14: Exercise should reference Figure 3.17, not Figure 3.18

## Chapter 4

page 154 (156):

- second paragraph: "we take advantage[s]"

page 160 (162):

- third paragraph: "and 50 virgini[n] (c) as"

page 163 (165):

- bottom paragraph: "Chapter 5, [Modeling with Linear Regression] (Model Comparison)"

page 167 (169):

- last line: "$x!$ is the factorial of $x$, that is, $x! = x \times (x-1) \times (x-2) \times \dots \times 2 \times 1$.

page 170 (172):

- equation (4.25): $$p(y_j = k_i) = \psi \frac{\mu^{x_i}e^{-\mu}}{x_i!}$$

page 175 (177):

- "Extensions such (as) the ones we [we] saw"


## Chapter 5

page 185 (187):

- first paragraph: "shocked or even disappoint[ing] (ed) by"
- equation 5.1: $p(  T_{sim} > T_{obs} | y)$



Page 216 (218):

- "KL diverge(nce) is useful because it is a way of measuring how close to distributins are

page 219 (221):

-  Bayes factors are problematic to use, given that they are very sensitive[ly] to prior specification,


## Chapter 6

page 230 (232):

- last paragraph: "does not necessary depend(s) on data"

page 237 (239):

- third paragraph: "what we do to turn logistic[s] regression into a"


page 238 (240):

- first paragraph: "someone already decide(d) the name"


page 239 (241):

- third paragraph: "br[ake] (eak) the stick"


page 241 (243):

- first paragraph: "represent(s) how confiden[ce] (t) we are"


page 245 (247):

- first paragraph: "This model also show(s) a less smooth"


page 247 (249):

- last paragraph: "the latent variable before doing inference, wi[n]ch may lead to"


page 248 (250):

- second paragraph:
    + "thus i[n] (t) may be convenient"
    + "th[is] (ese) models can lead"

- last paragraph: "can be interpreted as continuous mixture model(s)"


## Chapter 7

page 253 (255):

- last paragraph:
    + "we express the first [one] function"
    + "for the second [one] function"

page 255 (258):

- equation 7.4: second term on the RHS should be: $(x_2 - x_2')^2$
- third paragraph: "covariance matrix looks [appears] for different inputs"
- info box: "Thus, the close[st] (r) two points are on the x axis[;] (,) the mo[st] (re) similar we expect their values to be on the y axis"


page 259 (262):

- last paragraph: "and [this is not the exception with] Gaussian processes (are no exception)"

page 261 (264):

- second paragraph: "$x$ is the independent variable[s], and $y$ is the dependent variable[s]"
- third paragraph: "module, [Often, ]for length-scale parameters, priors avoiding zero (often) work better"

page 267 (270):

- first paragraph: "their geographical similar[ly] (ity)"

page 271 (274):

- second paragraph: "counteracting the effect of it('s)[ over] close neighbors"

page 279 (282):

- last paragraph: "to the time a disaster[s] happen[s] (ed)"

page 280 (283):

- first paragraph: "Let's load [at] the data"

page 285 (288):

- last paragraph: "We may imag[e] (ine) that"


## Chapter 8

page 295 (298):

- second paragraph: "[Also is] (It's also) one of the building block(s)"

page 303 (306):

- third paragraph: "The rule to decide whether to accept or reject is known as the Metropolis criteri[a] (on)"

page 304 (307):

- step 2, it should read Choose a new parameter value $x_{i+1}$ rather than Choose a new parameter value $x_i+1$.

- The uppercase Q's should be lowercase q's $q(x_{i+1} \mid x_i)$


page 318 (321):

- second paragraph: "samples from the noncentered model ha[s] (ve) almost no autocorrelation" 

page 319 (322):

- second paragraph: " we will need a [more] (larger) effective sample size"

page 327 (331):

- first paragraph:
    + "One book that is generally refere[e]d (to) as"
    + "You may also want to check (out) the book"


