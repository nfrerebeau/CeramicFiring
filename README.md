
<!-- README.md is generated from README.Rmd. Please edit that file -->

# archeosciences2019

[![DOI](https://zenodo.org/badge/DOI/xxx/xxx.svg)](https://doi.org/xxx/xxx)
[![GitHub
Release](https://img.shields.io/github/release/nfrerebeau/archeosciences2018.svg)](https://github.com/nfrerebeau/archeosciences2018/releases)
[![Travis-CI Build
Status](https://travis-ci.org/nfrerebeau/archeosciences2018.svg?branch=master)](https://travis-ci.org/nfrerebeau/archeosciences2018)

This repository contains the data and code for our paper (in french):

> Frerebeau, N. et Pernot, M. (2018). Dans la chaleur des fours : que
> restituer des pratiques des céramistes des sociétés anciennes ?.
> *Archéosciences, revue d’Archéométrie*, 42-2, p. 95-105. DOI :
> <https://doi.org/10.4000/archeosciences.6007>.

The files hosted in this repository are the development versions and may
have changed since the paper was published.

## How to cite

Please cite this compendium as:

> Frerebeau, N. and Pernot, M. (2019). *Compendium of R code and data
> for “Dans la chaleur des fours : que restituer des pratiques des
> céramistes des sociétés anciennes ?”*. Accessed YYYY-MM-DD. Online at
> <https://doi.org/xxx/xxx>.

## Licenses

**Text and figures:**
[CC-BY-SA-4.0](http://creativecommons.org/licenses/by-sa/4.0/).

**Code:** see the [DESCRIPTION](DESCRIPTION) file.

**Datasets:**
[CC-BY-SA-4.0](http://creativecommons.org/licenses/by-sa/4.0/).

## Instalation

You can download the compendium as a zip from from this
[URL](http://github.com/nfrerebeau/archeosciences2018/archive/master.zip).

Or you can install this compendium as an R package,
`archeosciences2018`, from GitHub with:

``` r
# install.packages("devtools")
remotes::install_github("nfrerebeau/archeosciences2018")
```

To download the package source as you see it on GitHub, for offline
browsing, use this line at the shell prompt (assuming you have Git
installed on your computer):

``` sh
git clone https://github.com/nfrerebeau/archeosciences2018.git
```

## Usage

Once the download is complete, open the `archeosciences2018.Rproj` in
RStudio to begin working with the package and compendium files.

The `analysis/` directory contains:

  - The Rmarkdown source file of the manuscript (in the `paper/`
    subdirectory),
  - All the figures generated from R code (in the `figures/`
    subdirectory),
  - All the raw data files (in CSV format, in the `data/` subdirectory),
  - Code files used for data cleaning (in the `scripts/` subdirectory).

The `R/` directory contains the custom R functions used in this project.
Datasets (in RDA format) are located in the `data/` directory.

## Dependencies

The original manuscript was produced with R 3.6.0. See the
[DESCRIPTION](DESCRIPTION) file for a full list of the packages that
this project depends on, including the suggested packages. The
`packrat/` directory contains the source code for all the packages we
depend on. If all works well, these will be installed on your machine
when you open `archeosciences2018.Rproj` in RStudio.
