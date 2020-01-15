# live: Local Interpretable (Model-agnostic) Visual Explanations

[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/live)](https://CRAN.R-project.org/package=live)
[![Downloads](http://cranlogs.r-pkg.org/badges/live)](https://CRAN.R-project.org/package=live)
[![Total Downloads](http://cranlogs.r-pkg.org/badges/grand-total/live?color=orange)](https://cranlogs.r-pkg.org/badges/grand-total/live)
[![Build Status](https://travis-ci.org/ModelOriented/live.svg?branch=master)](https://travis-ci.org/ModelOriented/live)
[![Coverage Status](https://img.shields.io/codecov/c/github/ModelOriented/live/master.svg)](https://codecov.io/github/ModelOriented/live?branch=master)
[![DOI](https://zenodo.org/badge/97615889.svg)](https://zenodo.org/badge/latestdoi/97615889)
[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=The%20live%20package%20will%20help%20you%20explain%20your%20model%27s%20predictions%20by%20fitting%20a%20simpler%20model%20locally%20and%20visualizing%20it.%20Find%20out%20more%20at%0Ahttps://github.com/MI2DataLab/live%0A&hashtags=rstats,interpretableML,machinelearning,xAI)


## Installation

To get started, install stable CRAN version:

```
install.packages("live")
```

or the development version:

```
devtools::install_github("ModelOriented/live")
```

[See the latest changes.](https://github.com/ModelOriented/live/blob/master/NEWS.md)

Features coming up next:

  * better support for comparing explanations for different models / different instances,
  
  * improved Shiny application (see `live_shiny` function in development version).

If you have any bug reports, feature requests or ideas to improve the methodology, feel free to leave an issue.


## Materials

Find the paper about `live` and [breakDown](https://github.com/pbiecek/breakDown) in [R Journal](https://journal.r-project.org/archive/2018/RJ-2018-072/index.html).

Website: https://mi2datalab.github.io/live/

Conference talks on `live`: [Wrocław 2018](https://github.com/mstaniak/Talks/raw/master/2018/Wroclaw_IX.pdf), [Berlin 2017](https://github.com/mstaniak/Talks/blob/master/2017/Berlin.pdf). 

Python implementation of LIME and info about the method: https://github.com/marcotcr/lime
