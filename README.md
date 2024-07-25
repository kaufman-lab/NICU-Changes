# NICU-Changes

## NICU data cleaning and geocoding

Geocoding was originally done by emblake23 using the GoogleMaps API.  Because our trial period has expired we cannot easily re-run this part of the code, so geocodes that needed to be added or edited after the trial period were done manually and merged with an export of the original geocodes.

## Exclusions
Locations in Puerto Rico were dropped.  Duplicated facilities (for example, facilties listed twice with different names but the same address and similar capacity) were flagged and dropped.


## Data Contributed By emblake23:

See original code and files at emblake23/NICU-Changes

They note:

"The shapefile used for Hawaii is included in zipped format, as the HI in the Tigris file did not contain the correct classification/grouping of islands based on our needs.

Finally, the three final map products are included.

Data Sources:

cleannicu96.csv: raw data from "NICUs and Neonatologist of the USA and Canada 1996 Directory" by American Academy of Pediatrics, 
cleannicu11.csv: raw data from "NICUs and Neonatologist of the USA and Canada 2011 Directory" by American Academy of Pediatrics,
cleannicu23.csv: raw data from The Neonatology Solutions NICU Directory, https://neonatologysolutions.com/nicu-directory/,
US county shapefiles: Census 2021 TIGER/Line Shapefiles brought in directly using the tigris package,
Hawaii shapefiles: Hawaii Statewide GIS Program https://geoportal.hawaii.gov/datasets/HiStateGIS::2020-census-county-boundaries/about"
