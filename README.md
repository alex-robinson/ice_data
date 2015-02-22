# ice_data

This respository is intended as a resource for ice sheet modelers. 
It constains several datasets from disparate sources that have been
processed using the 'coordinates' package onto the same grid. 

Files are separated by domain, e.g., Greenland or Antarctica, and then
they are organized by the grid representation, e.g., Bamber01-20km or GRL-10km.

Datasets are generally maintained in separate NetCDF files, with the naming convention
GRIDNAME\_DATASET.nc, where GRIDNAME is the name of the grid and DATASET is a descriptive
name to indicate the dataset origin. 

A list of available datasets and their origins is listed below. 

# Greenland

TOPO
Bamber et al. (2013), gridded topography of the Greenland ice sheet,
including surface elevation, bedrock elevation and 0cean-land-ice mask. 

# Antarctica

TOPO
BEDMAP2 gridded topography of Antarctica 

VEL 
Surface velocity field 
Rignot, E., Mouginot, J. and Scheuchl, B.: Ice Flow of the Antarctic Ice Sheet, 
Science, doi 10.1126/science.1208336, 2011.

ACC
Accumulation field 
Arthern, R. J., Winebrenner, D. P. and Vaughan, D. G.: Antarctic snow accumulation 
mapped using polarization of 4.3-cm wavelength microwave
emission, J. Geophys. Res., 111, D06107, doi:10.1029/2004JD005667, 2006.

"The map is derived from a compilation of field measurements. Satellite observations from AMSR-E and AVHRR instruments are used to guide the
interpolation. The effective resolution of the map is approximately 100 km. The estimates of root mean square percentage error apply to regional
averages at scales of around 100 km by 100 km. On smaller scales, additional deviations of 30% r.m.s. are likely. Values for locations subject to melt
may be unreliable. Units are (kg/m²/a), or (mm/a) water equivalent."

BMELT
Ice shelf basal melt field (actual estimated and steady-state)
Rignot, E., Jacobs, S., Mouginot, J. and 
Scheuchl, B., Ice-Shelf Melting Around Antarctica, 
Science, doi: 10.1126/science.1235798, 2013
