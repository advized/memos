# R memo

## Installation

*Note: to install a package, log as a root if you want it install into /usr/lib/R/library*

### Packages

* list library: library()
* install package: install.package("name_package")
* update package: update.packages()

#### Config. R and GRASS

First install:
1. libgdal-dev (in order to get the gdal-config file)
2. libproj-dev (in order to get proj_api.h)

Then:
1. install package spgrass6


## Basics
* know R object classe: class(object_name)
* list objects: ls()
* summarize statistics: summary(object_name)
* list column names in dataframe: names(object_name)

### R and GRASS

* To import a vector from GRASS to R: object_name <- readVECT6("your_grass_layer", ignore.stderr=TRUE)


### Ploting
