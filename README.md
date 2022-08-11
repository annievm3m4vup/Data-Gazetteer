# Data-Gazetteer-Files

## Gazetteer-Files from Census:
 - https://www.census.gov/geographies/reference-files/time-series/geo/gazetteer-files.html
 - county-level, city-level
 - land area, population, geographic coordinates
 - from 1990 forward
 - 1970, 1980: US Statistical Abstracts, County and City Data Books, Social Explorer
 
## Example: 
 - calculate distances: "vincenty"
      - create distance from census tracts to CBD using the Vincenty ado function where CBD (latitude, longitude) is (29.75728600, -95.36294600)
         - generate double ycoord = latit1
         - generate double xcoord = 1ongit1
         - vincenty ycoord xcoord 29.75728600 -95.36294600, hav(dcbd)
