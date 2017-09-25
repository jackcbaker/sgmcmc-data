# Data for `sgmcmc` package

This repository provides the example datasets for the `R` package [`sgmcmc`](https://stor-i.github.io/sgmcmc/), available on [CRAN](https://cran.r-project.org/web/packages/sgmcmc) and [Github](https://github.com/STOR-i/sgmcmc).

The repo contains the [covertype](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary.html) and [mnist](http://yann.lecun.com/exdb/mnist/) datasets. For more details on these datasets and their format see the `sgmcmc` package documentation. 

To get these datasets in `R`, install `sgmcmc` using `install.packages("sgmcmc")`, then load in the package using `library(sgmcmc)`. Finally use the `getDataset` function within the package. For example:
```
# Download and load covertype dataset
covertype = getDataset("covertype")

# Download and load mnist dataset
mnist = getDataset("mnist")
```
