# metscale
Temporal up and downscaling of meteorological data (from monthly to subhourly)

This is just an idea at the moment. The goal is to provide a set of functions that can up and downscale weather data (as used in crop models mostly) from monthly to sub-hourly. The S3 classes will be 'met_daily' (which will correspond to 'apsimx::met'), 'met_hourly', 'met_subdaily', 'met_subhourly'. I don't see having much use for 'met_monthly', but climate models provide data at this resolution, so I might eventually needed.

There are R packages for climate downscaling and I will look into those, but, in my preliminary investigation, none of them perform the type of daily to hourly downscaling that I need.
