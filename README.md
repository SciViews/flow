# flow - Workflow management and alternate pipe operator

[![Linux & OSX Build Status](https://travis-ci.com/SciViews/flow.svg )](https://travis-ci.com/SciViews/flow)
[![Win Build Status](https://ci.appveyor.com/api/projects/status/github/SciViews/flow?branch=master&svg=true)](https://ci.appveyor.com/project/phgrosjean/flow)
[![Coverage Status](https://img.shields.io/codecov/c/github/SciViews/flow/master.svg)
](https://codecov.io/github/SciViews/flow?branch=master)
[![CRAN Status](https://www.r-pkg.org/badges/version/flow)](https://cran.r-project.org/package=flow)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Installation

### Latest stable version

The latest stable version of **flow** can simply be installed from [CRAN](http://cran.r-project.org):

```r
install.packages("flow")
```


### Development version

Make sure you have the **devtools** R package installed:

```r
install.packages("devtools")
```

Use `install_github()` to install the **flow** package from Github (source from **master** branch will be recompiled on your machine):

```r
devtools::install_github("SciViews/flow", build_vignettes = TRUE)
```

R should install all required dependencies automatically, and then it should compile and install **flow**.

Latest devel version of **flow** (source + Windows binaires for the latest stable version of R at the time of compilation) is also available from [appveyor](https://ci.appveyor.com/project/phgrosjean/flow/build/artifacts).


## Usage

Make the **flow** package available in your R session:

```r
library("flow")
```

Get help about this package:

```r
library(help = "flow")
help("flow-package")
```

For further instructions, please, refer to these help pages.


## Note to developers

Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.
