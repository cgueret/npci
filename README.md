Contains R code to fit non-parmetric causal inference models. Of particular interest are the calculations in the examples folder.

To run the examples, first install the package by running, from within R

```
install.packages(c("rstan", "Rcpp", "tgp", "V8"))
install.packages("path/to/repository", type = "source", repos = NULL)
```

or from the command line

    R CMD INSTALL path/to/repository

You will need to have installed the library V8 beforehand.


The file `examples/toy/generatePlots.R` contains code to produce the toy data example. The simulation data can be simply loaded by running `examples/ihdp_sim/loadData.R`, or the simulations produced by running either `examples/ihdp_sim/runLocally.R` or `examples/ihdp_sim/queueJobs.R` (if on a cluster using TORQUE). Change your working directory before doing any of the above.
