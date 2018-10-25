# PyConDE2018 - Presentation 


## Measuring the hay in the haystack: quantifying hidden variables using Bayesian Inference

Technology-driven trading is a field with many challenges, and performance and availability of the network communication is essential to the business. To have a good understanding on the performance and availability, we monitor certain metrics - however not every interesting metric is readily available to measure. Some of these have to be inferred from the data we see in production by incorporating our own knowledge. What complicates this further is that the relationship between the hidden variables and the output data is not a deterministic one, as we are often dealing with a stochastic system.

Bayesian inference is a suitable way to tackle this issue - it allows encoding our knowledge as a prior distribution of the model parameters. Here we will go through real-world uses of Bayesian inference at IMC, using PyMC3 to make an estimate for the hidden metrics in the network traffic.

Knowledge: No prior knowledge of PyMC3 is required. Since this is a short presentation, the talk with approach the problem and the solution at a high level instead of implementation details.


## Contents
- Dataset (synthetic)
- Slides
- Notebook
