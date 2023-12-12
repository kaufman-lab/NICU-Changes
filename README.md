# NICU-Changes

The Rmd file (final_nicumaps.Rmd) can be used to create US maps showing the changes in the number of NICUs by county from 1996-2011, 2011-2023, and 1996-2023, using the three individual NICU directory files (cleannicXX.csv)

Additionally, the shapefile used for Hawaii is included in zipped format, as the HI in the Tigris file did not contain the correct classification/grouping of islands based on our needs.

Finally, the three final map products are included.

Data Sources:

cleannicu96.csv: raw data from "NICUs and Neonatologist of the USA and Canada 1996 Directory" by American Academy of Pediatrics, 
cleannicu11.csv: raw data from "NICUs and Neonatologist of the USA and Canada 2011 Directory" by American Academy of Pediatrics,
cleannicu23.csv: raw data from The Neonatology Solutions NICU Directory, https://neonatologysolutions.com/nicu-directory/,
US county shapefiles: Census 2021 TIGER/Line Shapefiles brought in directly using the tigris package,
Hawaii shapefiles: Hawaii Statewide GIS Program https://geoportal.hawaii.gov/datasets/HiStateGIS::2020-census-county-boundaries/about
