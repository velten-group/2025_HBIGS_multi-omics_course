# HBIGS course 2025 

This repository contains the material for the practical sessions of the course "Introduction to Omics Data Integration and Multi-Omic Data Analysis” at HBIGS at Heidelberg university.

## Preparations

1. For the course you need to bring a laptop with R (version 4.4) (https://cran.r-project.org/) and RStudio (https://posit.co/products/open-source/rstudio/) installed. 

2. Once you have installed R and RStudio, please download and open [welcome.Rmd](https://github.com/velten-group/2025_HBIGS_multi-omics_course/blob/main/welcome.Rmd). Follow the instructions in the markdown to verify that you have a working R installation setup, install the mentioned packages and knit it to check that you have everything set up correctly before the start of the course.

## Lecture slides
The lecture slides for the course can be downloaded from Heibox: https://heibox.uni-heidelberg.de/d/2a7bdb94784a43cc8c79/ 

## Installation tips
In case lisi package installation fails:
For macOS users: try downloading and installing GNU Fortran compiler from: https://mac.r-project.org/tools/
For Windows users: 
  1) Go to https://cran.r-project.org/bin/windows/Rtools/
  2) Download the version that matches your version of R. For example: R 4.3 → Rtools43 ; R 4.4 → Rtools44
  3) Run in Rstudio: pkgbuild::has_build_tools(debug = TRUE), it should return True
