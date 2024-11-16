# R_Analysis_of_US_Census_Data

A [Quarto website](https://quarto.org/docs/websites/) with R scripts and html files that follows the book [Analyzing US Census Data: Methods, Maps, and Models in R](https://walker-data.com/census-r/) by Kyle Walker with R scripts in acquisition, wrangling, and ggplot2 based plotting. Functions from the R package [RcensusPkg](https://github.com/deandevl/RcensusPkg) are extensively used in interfacing with the Census Bureau's API.

Efficient manipulations of this data are presented using the R package [data.table](https://cran.r-project.org/web/packages/data.table/index.html). [RspatialPkg](https://github.com/deandevl/RspatialPkg) combines Census Bureau spatial geographic features with survey data to create ggplot2 based choropleth maps. Also, the R package [RplotterPkg](https://github.com/deandevl/RplotterPkg) is shown to provide an easy interface to both static and interactive ggplot2 plotting such as histograms, bar charts, and scatterplots.

The `RcensusPkg`, `RspatialPkg`, and `RplotterPkg` are currently available from GitHub and installed via `devtools::install_github()`.
