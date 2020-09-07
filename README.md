
<!-- README.md is generated from README.Rmd. Please edit that file -->

# CruzPlot

<!-- badges: start -->

[![Travis build
status](https://travis-ci.com/smwoodman/CruzPlot.svg?branch=master)](https://travis-ci.com/smwoodman/CruzPlot)
[![AppVeyor build
status](https://ci.appveyor.com/api/projects/status/github/smwoodman/CruzPlot?branch=master&svg=true)](https://ci.appveyor.com/project/smwoodman/CruzPlot)
<!-- badges: end -->

CruzPlot is an R package that contains a GUI for creating maps, plotting
data, and performing basic data summaries from data files in the “DAS”
format produced by WinCruz.

## Installation

You can install CruzPlot from [GitHub](https://github.com/) with:

``` r
# install.packages("remotes") # Install remotes package if needed
remotes::install_github("smwoodman/swfscDAS", build_vignettes = TRUE)
remotes::install_github("smwoodman/CruzPlot")
```

Note that CruzPlot depends on swfscDAS, and thus you should ensure that
[swfscDAS](https://smwoodman.github.io/swfscDAS/) is installed and
updated as well. Running the above code will ensure the latest versions
of both packages are installed. However, if you want to force an
installation, you can run:

``` r
remotes::install_github("smwoodman/swfscDAS", force = TRUE, build_vignettes = TRUE)
remotes::install_github("smwoodman/CruzPlot", force = TRUE)
```

Before installing CruzPlot, you must have
[R](https://www.r-project.org/),
[RStudio](https://rstudio.com/products/rstudio/download/#download), and
the appropriate version of
[Rtools](https://cran.r-project.org/bin/windows/Rtools/) installed. It
is best practice to install after closing all instances of R and
RStudio, and then running the install code from the R GUI rather than
RStudio. Please contact the developer if you have any issues.

After updating, it is recommended to create and save new workspaces,
rather than using workspaces saved with a previous version of CruzPlot.

## Running CruzPlot

To open and run CruzPlot, run the following code in RStudio:

``` r
CruzPlot::cruzplot_gui()
```

If text or images overlap within the CruzPlot window, you can make the
browser window full screen or adjust the text size in your browser
(e.g., Ctrl - minus (‘-’) on Windows systems)

## CruzPlot manual

The CruzPlot manual can be downloaded [at this
link](https://github.com/smwoodman/CruzPlot/blob/master/inst/shiny/www/CruzPlot_Manual_app.pdf),
or accessed when running CruzPlot by opening the “CruzPlot Manual” page.
It is recommended for new users to read the first two pages of the
manual for orientation purposes; the rest of the manual contains
section-specific information (formatting requirements, etc.) and can be
read on an as-needed basis.
