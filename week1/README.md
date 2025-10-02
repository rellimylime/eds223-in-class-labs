# Week 1 Lab: Making Maps in R with `tmap`

## Overview

This lab introduces the fundamentals of creating thematic maps in R using the `tmap` package. We explore basic map-making principles, coordinate reference systems, and techniques for visualizing spatial data effectively.

## Learning Objectives

- Understand the fundamentals of good map design
- Create basic thematic maps using `tmap`
- Work with different coordinate reference systems (CRS)
- Apply styling and customization to maps
- Export maps for use in reports and presentations

## Lab Contents

- `week1-lab.qmd` - Quarto document containing lab code and analysis
- `data/` - Folder containing spatial datasets used in the lab

## Data

## Data Sources

Data files used in this lab are located in the `data/` folder. [Add specific dataset descriptions here, for example:]

- **Dataset Name**: Brief description
- **Source**: Where it came from
- **Format**: Shapefile, GeoJSON, etc.

## Key Topics

1. **Map Design Principles**
   - Elements of a good map
   - Choosing appropriate map types
   - Color schemes and symbolization

2. **Coordinate Reference Systems**
   - Geographic vs. projected coordinate systems
   - Understanding CRS in spatial analysis
   - Transforming between coordinate systems

3. **`tmap` Basics**
   - `tm_shape()` and layering
   - `tm_polygons()`, `tm_borders()`, `tm_fill()`
   - Map layouts and legends
   - Interactive vs. static maps

## Required Packages

```r
library(tmap)      # Thematic mapping
library(sf)        # Simple features
library(here)      # File path management
library(tidyverse) # Data manipulation
```

## Getting Started

1. Open `week1-lab.qmd` in RStudio
2. Ensure all required packages are installed
3. Run the code chunks sequentially

## Additional Resources

- [tmap documentation](https://r-tmap.github.io/tmap/)
- [tmap book](https://r-tmap.github.io/tmap-book/)
- [Geocomputation with R - Chapter 9](https://geocompr.robinlovelace.net/adv-map.html)
- [Course lecture slides](https://docs.google.com/presentation/d/1hMWl_QV6Z7gvUg4gRjSm3-0lSs1vW5_3fsaJ5Kvj_xY/present)

