#MetaMicrobiome: an R package for the meta-analysis and visualization of microbiome.
MetaMicrobiome was designed to performance the meta-analysis, visualization and the module building. MetaMicrobiome provides function for computing the count data for the measures of risk and a chi-squared test. the package also provides a function for creating forest plots for the results of the measures of risk. Moreover, the package also provides functions for the module building and testing based on the randomforest, and a function for the visualization for the result with the ROC curves.
##Getting Started
These instructions will get you a copy of the package and running on your local machine for using, development and testing purpose.
###Dependencies
MetaMicrobiome requires the packages of [metafor](http://www.metafor-project.org/doku.php/installation), [eipR](https://cran.r-project.org/web/packages/epiR/index.html), [pROC](https://cran.r-project.org/web/packages/pROC/index.html), [caret](https://cran.r-project.org/web/packages/caret/index.html), [ggplot2](https://cran.r-project.org/web/packages/ggplot2/index.html), [dplyr](https://cran.r-project.org/web/packages/dplyr/index.html) and [tidyr](https://cran.r-project.org/web/packages/tidyr/index.html)
###Installing
####Install the developement version from GitHub:
```
devtools::install_github('xiangpin/MetaMicrobiome')
```
Or 
```
git clone https://github.com/xiangpin/MetaMicrobiome.git
R CMD build MetaMicrobiome
R CMD INSTALL MetaMicrobiome_version.tar.gz
```
####Try it out
```
require("MetaMicrobiome")
example(ggforest)
```
##Documentation


##Authors
Shunagbin Xu  
Email: xshuangbin@163.com  
Github: https://github.com/xiangpin/
##Citation

##Contributing
