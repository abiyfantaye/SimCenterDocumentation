.. _lbl-future_quoFEM:

.. role:: blue

*************
Release Plans
*************

The following features are planned to be developed for upcoming releases of |app|. We are actively working on the features in the next release. Farther development priorities may change depending on feedback from the community. If you have any suggestions, we encourage you to contribute and contact us through the SimCenter Forum.

      
November 2024
-------------
   #. Accelerate Bayesian calibration using advanced Markov Chain Monte Carlo methods (1.2.3.4) - Build a surrogate model iteratively that will replace the original model in MCMC sampling. In each iteration, use a batch of data generated by evaluating the original model at carefully selected points to improve the surrogate model approximation of the target probability density. This is especially helpful when the original model is expensive to run and conventional MCMC is not feasible.


 .. note::

    The numbers in parentheses are for internal tracking purposes.
