This fork is a slightly modified crestree package, which was used for the following research paper:

Soldatov, R. et al. Spatiotemporal structure of cell fate decisions in murine neural crest. Science (80-. ). 364, (2019).

The modifications are the following:
- allow to select 2 roots (with consistent projection of the cells on the tree)
- allow to select any point on the tree as a root
- allow to perform test for associated genes on s subset of cells that is not an entire branch
- addition of progress bars for time consuming processes
- various fixes for visualisation of gene clusters

# crestree
A set of methods developed to model cell fate decision landscape of early mouse neural crest.

A walkthrough guide for modelling transcriptional tree is described in https://github.com/hms-dbmi/crestree/blob/master/vignettes/tree_guide.md

Analysis of bifurcation point, using sensory-autonomic bifurcation as example, is described in https://github.com/hms-dbmi/crestree/blob/master/vignettes/bifurcation_point.md


## Installation instructions

```{r setup}
install.packages("devtools")
devtools::install_github("hms-dbmi/crestree")
library(crestree)
```
