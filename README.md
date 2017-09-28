# LAF: Locally Adaptive Factor (LAF) processes for multivariate time series

This repository is associated with the paper Durante, Scarpa and Dunson (2014). [*Locally Adaptive Factor Processes for Multivariate Time Series*](http://jmlr.org/papers/v15/durante14a.html). Journal of Machine Learning Research, 15:1493—1522, and aims at providing **code and materials to implement the Gibbs sampler algorithm for the mean-covariance regression model described in the paper**. Readers interested in this topic can also refer to the NIPS paper Durante, Scarpa and Dunson (2013). [*Locally Adaptive Bayesian Multivariate Time Series*](http://papers.nips.cc/paper/5115-locally-adaptive-bayesian-multivariate-time-series), Advances in Neural Information Processing Systems, 26:1664—1672.

Here we provide the `Julia` implementation from [jmxpearson](https://github.com/jmxpearson), with additional comments and guidelines. For a version of the Gibbs sample code in `Python` refer to the [original repository](https://github.com/jmxpearson/laf) from [jmxpearson](https://github.com/jmxpearson).

The codes can be found in the directory [julia](https://github.com/danieledurante/LAF/tree/master/julia) and requires the following **dependencies**: 

    - Julia 0.4+ (dev branch as of this testing)
    - PyPlot (for plotting)
    - Distributions


