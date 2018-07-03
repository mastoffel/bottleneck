# Analysis workflow for "Recent demographic histories and genetic diversity across pinnipeds are shaped by anthropogenic interactions and mediated by ecology and life-history", Stoffel et al.

## Overview

The complete analysis workflow is split into two repositories:

(1) Coalescent simulations and ABC analysis
- repository: https://github.com/mastoffel/Pinniped_bottleneck_CoalSimABC
- the scripts in this repository should run on a server with sufficient computing power and memory

(2) All further analyses are in the current directory
- repository: https://github.com/mastoffel/pinniped_bottlenecks
- these scripts can be run a standard desktop machine
- the scripts to reproduce the main results including the figures have been placed in the R folder
and are sequentially named from 01 to 14. Supplementary analyses, figures and tables can be reproduced
based on the remaining scripts.

In addition, we packaged some specific functions into two packages:
(a) sealABC:  devtools::install_github("mastoffel/sealABC")
(b) mcmcR2:   devtools::install_github("mastoffel/mcmcR2")

Both packages are highly specific to the current analysis and probably have to be modified to 
be of use in other projects.


