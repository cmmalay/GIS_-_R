# GIS and R

## Why use R over a desktop GIS?
R is free and open source whereas some licenses for a traditional desktop GIS can cost thousands. The R language is also reproducible in ways that desktop GIS are not. There is also a greater shareability of R scripts and packages. R was designed for statistical computing so it works well for spatial statistics. R also offers a wide range of statistical and visualizaiton libraries. 

## Pre-Requirements
* R
* RStudio

### Packages to Install
```bash
sp
sf
tidyverse
rmapshaper
```
#### sp Package - provides classes and methods for spatial data. Includes functions that provide plotting abilities and spatial selection.
#### sf Package - supports simple features. Allows for geometrical operations and conversions. 
#### tidyverse Package - set of packages that work together. 
#### rmapshaper Package - allows for polygon simplfication. 

### Basic GIS abilities in R
* Creating sf Objects - can store geospatial and attribute data in a spatial dataframe. 
* Inspection - can retrieve spatial information about an object's features. 
* Manipulation - allows for data operations.
* Preparation - can join spatial dataframes with other dataframes and add new variables. 
* Calculations - can calculate area. 
* Visualization - can simplify geometries and produce maps. 

