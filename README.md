# modelling-the-age-of-the-oldest-person-in-the-world
Supplementary Python code for optimizing parameters in a stochastic model describing the age of the world's oldest person.

This repository contains supplementary Python code corresponding to the optimization process described in the article "Modelling the distribution of longevity leaders" by Csaba Kiss, László Németh, and Bálint Vető. The article proposes a stochastic model to describe the evolution of the age of the world's oldest person, utilizing a dataset collected by the Gerontology Research Group since 1955.

The Python code provided here implements the Nelder-Mead optimization method to compute maximum likelihood estimates for the parameters of the proposed model. These parameters include $\alpha$, $K$, $b$, $c$, and $\gamma$, which are fitted to the statistics of the oldest person titleholder data.

The optimization process aims to find the optimal parameter values that provide a good fit to the data while ensuring a realistic lifespan distribution. The code is organized to facilitate reproducibility of the results presented in the article.
