# SplicingFactory R package

The SplicingFactory R package uses transcript-level expression
values to analyze splicing diversity based on various statistical measures,
like Shannon entropy or the Gini index. These measures can quantify
transcript isoform diversity within samples or between conditions.
Additionally, the package analyzes the isoform diversity data, looking for
significant changes between conditions.

## Installation

You can install SplicingFactory from github with:

```R
install.packages("devtools")
devtools::install_github("SU-CompBio/SplicingFactory")
```