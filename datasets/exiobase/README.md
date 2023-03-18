# Exiobase

The monetary emission factors will be pulled from this [Exiobase](https://zenodo.org/record/5589597#.Yh9_Zi8w1ao).
It provides provides a time series of monetary emission factors tables ranging from 1995 to a recent year for 44 countries (28 EU member plus 16 major economies) and five rest of the world regions.

The main benefits with this datasource is to have emission factors computed consistently across region and over time. Yearly emission factors are needed by MyCityCO2 in order to deal with inflation.

The files are coming from the yearly files IOT_{year}_pxp.zip . Within this zip, the file to use sits under \impacts\M.txt and the line to read in order to retrieve GHG emissions is named : "GHG emissions AR5 (GWP100) | GWP100 (IPCC, 2010)"