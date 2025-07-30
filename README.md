This project visualizes Vienna’s U-Bahn (subway) network using R and the Leaflet package. It provides an interactive map displaying all five subway lines and 27 stations, with tooltips that reveal station metadata when hovered over.

# Features
- Interactive Leaflet map rendered in R
- Metadata tooltips for each subway station
- Color-coded lines for U1–U6
- Clean geospatial layout using shapefiles and base maps

# Folder Structure
```
metro-ahennessy/
├── data/                        # CSVs and shapefiles used to render map
├── AH_Vienna_Project.qmd       # Main Quarto notebook
├── AH-Vienna-Metro-Map.Rproj   # RStudio project file
├── README.md                   # This file
└── .gitignore
```

# Getting Started

# Requirements
- R (>= 4.0)
- RStudio (recommended)
- Packages:
  - `leaflet`
  - `sf`
  - `tidyverse`
  - `dplyr`
  - `quarto`

You can install required packages with:

```r
install.packages(c("leaflet", "sf", "tidyverse", "dplyr"))
```

# Render the Map
1. Open `AH-Vienna-Metro-Map.Rproj` in RStudio.
2. Open `AH_Vienna_Project.qmd`.
3. Click **Render** or knit the document to HTML.

# Project Motivation

This project was created to explore geospatial visualization and interactive web maps using public transit data. It integrates spatial data, data cleaning, and visual storytelling using the R geospatial stack.

# Author
**Aidan Hennessy**  
American University Graduate Student – Data Science  
[GitHub Profile](https://github.com/ahennessy25)
