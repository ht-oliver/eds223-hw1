# Exploring Environmental Justice in Wayne County, Michigan
Map making practice for EDS 223 - Environmental Injustice in Wayne County, Michigan


## Purpose
The purpose of this repository is to house that data and scripts that produce metrics on environmental injustice in Wayne County, Michigan. Specifically, the report produced in this repository seeks to test the hypothesis that lower-income communities are more likely to be located near hazardous waste disposal sites than their high-income counterparts.

## Contents
```

├── data: # Data is not present in repository. See Data Access section for download instructions
│   ├── ejscreen
│   ├── GL250515_lam
│   └── tl_2017_26_place
├── docs
│   └── ej_screen.qmd #Rendering this document produces environmental justice analysis
|
├── EDS 223 HW#1.pdf
|
├── env_injustice_Wayne_MI.Rproj
|
├── ej_screen_files
│   ├── figure-html
│   ├── figure-pdf
│   └── libs
│       ├── bootstrap
│       ├── clipboard
│       │   └── clipboard.min.js
│       └── quarto-html
├── README.html
└── README.md
```

## Data Access
The raw data used in this analysis is publicly available and can be downloaded at the sources below. This raw data should be downloaded and placed in a folder titled "data" in the home directory for the repository. The following are links to the datasets used in analysis:

EPA Census Tract Data<sup>1</sup>:

https://drive.google.com/file/d/1nG6Nj1bXfzQFOVMO8Km3eNy4SWu1YcIQ/view


Michigan Cities Shapefile<sup>2</sup>:

https://catalog.data.gov/dataset/tiger-line-shapefile-2017-state-michigan-current-place-state-based


Great Lakes Shapefile<sup>3</sup>:

https://usicecenter.gov/Products/GreatLakesData


## Instructions

After installing the data listed above, the only step necessary to produce the Wayne County environmental justice analysis is to open the 'ej_screen.qmd' quarto document (housed in the 'docs' folder) and render it in RStudio or other compatible software. This will produce an html file with all relevant code and figures.

## Authors

Primary Author - Henry Oliver


## References

<sup>1</sup> U.S. Environmental Protection Agency (EPA), 2023. EJScreen Technical Documentation.

<sup>2</sup> U.S. Census Bureau. (n.d.). TIGER/Line shapefile, 2017, Michigan current place (state‑based) [Data set] https://catalog.data.gov/dataset/tiger-line-shapefile-2017-state-michigan-current-place-state-based

<sup>3</sup> U.S. National Ice Center. (n.d.). Great Lakes data support files. Retrieved October 6, 2025, from https://usicecenter.gov/Products/GreatLakesData


