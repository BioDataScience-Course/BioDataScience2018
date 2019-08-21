# BioDataScience2018 - Learnr Documents

[![Linux & OSX Build Status](https://travis-ci.org/SciViews/BioDataScience2018.svg )](https://travis-ci.org/SciViews/BioDataScience2018)
[![Win Build Status](https://ci.appveyor.com/api/projects/status/github/SciViews/BioDataScience2018?branch=master&svg=true)](http://ci.appveyor.com/project/phgrosjean/BioDataScience2018)
[![Coverage Status](https://img.shields.io/codecov/c/github/SciViews/BioDataScience2018/master.svg)
](https://codecov.io/github/SciViews/BioDataScience2018?branch=master)
[![CRAN Status](http://www.r-pkg.org/badges/version/BioDataScience2018)](http://cran.r-project.org/package=BioDataScience2018)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)


## Installation

### Latest stable version

The latest stable version of **BioDataScience** can be found on the [BioDataScience repository](https://github.com/BioDataScience-Course/BioDataScience.git)


### Development version

Make sure you have the **devtools** R package installed:

```r
install.packages("devtools")
```

Use `install_github()` to install the **BioDataScience2018** package from Github (source from **master** branch will be recompiled on your machine):

```r
devtools::install_github("BioDataScience-Course/BioDataScience2018")
```

R should install all required dependencies automatically, and then it should compile and install **BioDataScience2018**.

Latest devel version of **BioDataScience2018** (source + Windows binaires for the latest stable version of R at the time of compilation) is also available from [appveyor](https://ci.appveyor.com/project/phgrosjean/BioDataScience2018/build/artifacts).


## Usage

Make the **BioDataScience2018** package available in your R session:

```r
library("BioDataScience2018")
```

Get help about this package:

```r
library(help = "BioDataScience2018")
help("BioDataScience2018-package")
```

For further instructions, please, refer to these help pages.


## Note to developers

Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.
