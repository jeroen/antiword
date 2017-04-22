# antiword

[![Build Status](https://travis-ci.org/ropensci/antiword.svg?branch=master)](https://travis-ci.org/ropensci/antiword)
[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/ropensci/antiword?branch=master&svg=true)](https://ci.appveyor.com/project/ropensci/antiword)
[![Coverage Status](https://codecov.io/github/ropensci/antiword/coverage.svg?branch=master)](https://codecov.io/github/ropensci/antiword?branch=master)
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/antiword)](http://cran.r-project.org/package=antiword)
[![CRAN RStudio mirror downloads](http://cranlogs.r-pkg.org/badges/antiword)](http://cran.r-project.org/web/packages/antiword/index.html)

> Extract Text from Microsoft Word Documents

## Installation

```
devtools::install_github("ropensci/antiword")
```

## Hello World

The function has only a single function `antiword()`. It takes either a local 
file path or a URL to a word document:

```r
library(antiword)
text <- antiword("www.hrusa.org/thisismyhome/project/documents/UDHR-PlainEnglishVersion.doc")
cat(text)
```
