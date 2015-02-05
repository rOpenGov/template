---
title: "template tutorial"
author: rOpenGov core team
date: "2015-02-05"
output:
  html_document:
    theme: flatly
---
<!--
%\VignetteEngine{knitr::rmarkdown}
%\VignetteIndexEntry{template Markdown Vignette}
%\usepackage[utf8]{inputenc}
-->


Template package
===========

This R package provides a template for new packages. Your [bug reports and other
feedback](https://github.com/ropengov/template) are welcome! 


## Installation

Test the installation by loading the library:


```r
library(template)
```

Development version for developers:


```r
library(devtools)
install_github("ropengov/template")
```

We also recommend setting the UTF-8 encoding:


```r
Sys.setlocale(locale="UTF-8") 
```


**Validate Finnish personal identification number:**


```r
valid_hetu("010101-0101") # TRUE/FALSE
```

```
## [1] TRUE
```


```r
data(iris)
plot(Sepal.Length ~ Sepal.Width, iris) 
```

![plot of chunk regressionline](figure/regressionline-1.png) 

## Licensing and Citations

This work can be freely used, modified and distributed under the 
[Two-clause BSD license](http://en.wikipedia.org/wiki/BSD\_licenses).


```r
citation("template")
```

```
## 
## Kindly cite the sorvi R package as follows:
## 
##   (C) Leo Lahti (rOpenGov 2015).  template: Minimal package
##   template URL: http://github.com/ropengov/template
## 
## A BibTeX entry for LaTeX users is
## 
##   @Misc{,
##     title = {template: minimal package},
##     author = {Leo Lahti},
##     doi = {10.5281/zenodo.xxxxxxxx},
##     year = {2015},
##   }
## 
## Many thanks for all contributors! See: http://ropengov.github.io
```

## Session info

This vignette was created with


```r
sessionInfo()
```

```
## R version 3.1.2 (2014-10-31)
## Platform: x86_64-pc-linux-gnu (64-bit)
## 
## locale:
##  [1] LC_CTYPE=en_US.UTF-8       LC_NUMERIC=C              
##  [3] LC_TIME=en_US.UTF-8        LC_COLLATE=en_US.UTF-8    
##  [5] LC_MONETARY=en_US.UTF-8    LC_MESSAGES=en_US.UTF-8   
##  [7] LC_PAPER=en_US.UTF-8       LC_NAME=C                 
##  [9] LC_ADDRESS=C               LC_TELEPHONE=C            
## [11] LC_MEASUREMENT=en_US.UTF-8 LC_IDENTIFICATION=C       
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## other attached packages:
## [1] template_0.1.10 knitr_1.8      
## 
## loaded via a namespace (and not attached):
##  [1] assertthat_0.1 DBI_0.3.1      dplyr_0.3.0.2  evaluate_0.5.5
##  [5] formatR_1.0    magrittr_1.0.1 parallel_3.1.2 Rcpp_0.11.3   
##  [9] stringr_0.6.2  tools_3.1.2
```





