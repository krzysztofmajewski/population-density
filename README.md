DATA SOURCES

Population per FSA:

https://www.dropbox.com/s/je1wz2tj9rw8vvj/PopulationDensity.csv?dl=0
via
https://stackoverflow.com/questions/32622174/plotting-population-density-map-in-r-with-geom-point/50954020#50954020

Population per FSA, 2011 Census:

http://www12.statcan.gc.ca/census-recensement/2011/dp-pd/hlt-fst/pd-pl/Table-Tableau.cfm?LANG=Eng&T=1201&SR=1&S=22&O=A&RPP=9999&PR=0&CMA=0

Surface area per postal code (2006):

https://mdl.library.utoronto.ca/sites/default/files/mdldata/open/canada/national/statcan/geo/2006/ref_products/ut/fsa_area_2006.csv
via
https://mdl.library.utoronto.ca/collections/numeric-data/census-canada/2006/geo

Boundary (shape) files, 2011 Census:

https://www12.statcan.gc.ca/census-recensement/2011/geo/bound-limit/bound-limit-2011-eng.cfm


TODO

Find FSA surface area data from 2011 Census
Use 2016 Census data for everything?
Check if FSAs have changed between the population data set (Dropbox link) and surface area data set.
  Yes, some are absent in 2006 surface area data, see postal-code-notes.txt
Check H4T and L4V FSAs: make sure they really have zero population.
Get Canada shape file via URL?



TIPS

To find your FSA on Google Maps, just search in Google: `H2V postal code`
