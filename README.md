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

__TOPO-B13__

Topography of the Greenland ice sheet

Bamber, J. L., Griggs, J. A., Hurkmans, R. T. W. L., Dowdeswell, J. A., 
Gogineni, S. P., Howat, I., Mouginot, J., Paden, J., Palmer, S., Rignot, E.,
and Steinhage, D.: 
A new bed elevation dataset for Greenland, The Cryosphere, 7, 499-510, 
doi:10.5194/tc-7-499-2013, 2013.

http://www.the-cryosphere.net/7/499/2013/tc-7-499-2013.html

__TOPO-M14__

* TO DO * 
Topography of the Greenland ice sheet

Nature Geoscience, 2014. 

__TOPO-B01__

* TO DO * 

Topography of the Greenland ice sheet

Bamber, J. L. ... 2001.

__BASINS-nasa__

Greenland drainage basins mapped by NASA

Zwally, J. H.., Giovinetto, M. B., Beckley, M. A., and Saba, J. L.: 
Antarctic and Greenland Drainage Systems, GSFC Cryospheric Sciences
Laboratory, 2012

http://icesat4.gsfc.nasa.gov/cryo_data/ant_grn_drainage_systems.php

# Antarctica

__TOPO-BEDMAP2__

BEDMAP2 gridded topography of Antarctica
 
Fretwell, P., Pritchard, H. D., Vaughan, D. G., Bamber, J. L., Barrand, N. E., Bell, R., Bianchi, C., Bingham, R. G., Blankenship, D. D., Casassa, G.,
Catania, G., Callens, D., Conway, H., Cook, A. J., Corr, H. F. J., Damaske, D., Damm, V., Ferraccioli, F., Forsberg, R., Fujita, S., Gim, Y.,
Gogineni, P., Griggs, J. A., Hindmarsh, R. C. A., Holmlund, P., Holt, J. W., Jacobel, R. W., Jenkins, A., Jokat, W., Jordan, T., King, E. C., Kohler,
J., Krabill, W., Riger-Kusk, M., Langley, K. A., Leitchenkov, G., Leuschen, C., Luyendyk, B. P., Matsuoka, K., Mouginot, J., Nitsche, F. O., Nogi, Y.,
Nost, O. A., Popov, S. V., Rignot, E., Rippin, D. M., Rivera, A., Roberts, J., Ross, N., Siegert, M. J., Smith, A. M., Steinhage, D., Studinger, M.,
Sun, B., Tinto, B. K., Welch, B. C., Wilson, D., Young, D. A., Xiangbin, C., and Zirizzotti, A.: Bedmap2: improved ice bed, surface and thickness
datasets for Antarctica, The Cryosphere, 7, 375-393, doi:10.5194/tc-7-375-2013, 2013.

http://www.the-cryosphere.net/7/375/2013/tc-7-375-2013.html
http://www.antarctica.ac.uk//bas\_research/our\_research/az/bedmap2/

__BASINS-nasa__

Antarctic drainage basins mapped by NASA

Zwally, J. H.., Giovinetto, M. B., Beckley, M. A., and Saba, J. L.: 
Antarctic and Greenland Drainage Systems, GSFC Cryospheric Sciences
Laboratory, 2012

http://icesat4.gsfc.nasa.gov/cryo_data/ant_grn_drainage_systems.php

__VEL-R11__ 

Surface velocity field 

Rignot, E., Mouginot, J. and Scheuchl, B.: Ice Flow of the Antarctic Ice Sheet, 
Science, doi 10.1126/science.1208336, 2011.

These files give the Antarctic surface velocity map of Rignot et al. (2011)
on the same grid, with the same projection and in the same file formats as
bedmap2.

__ACC-A06__

Accumulation field 

Arthern, R. J., Winebrenner, D. P. and Vaughan, D. G.: Antarctic snow accumulation 
mapped using polarization of 4.3-cm wavelength microwave
emission, J. Geophys. Res., 111, D06107, doi:10.1029/2004JD005667, 2006.

> The map is derived from a compilation of field measurements. Satellite observations from AMSR-E and AVHRR instruments are used to guide the
> interpolation. The effective resolution of the map is approximately 100 km. The estimates of root mean square percentage error apply to regional
> averages at scales of around 100 km by 100 km. On smaller scales, additional deviations of 30% r.m.s. are likely. Values for locations subject to melt
> may be unreliable. Units are (kg/m²/a), or (mm/a) water equivalent.

__BMELT-R13__

Ice shelf basal melt field (actual estimated and steady-state)

Rignot, E., Jacobs, S., Mouginot, J. and 
Scheuchl, B., Ice-Shelf Melting Around Antarctica, 
Science, doi: 10.1126/science.1235798, 2013
