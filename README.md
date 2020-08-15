# TODO:
+ Look into x-array for handling satellite data

Objective: 
1. Get current graphs up-to-date w/ most recent satellite data
2. Incorporate old cruises
  + Get all data into standardized format
  + In Excel, play around with HC/FT data until everything *looks* correct
  + Implement in python to get relationship
  + Create new plots, lookup
3. Incorporate more bgc floats


+ Chl-a data info: https://oceancolor.gsfc.nasa.gov/atbd/chlor_a/
"The current implementation for the default chlorophyll algorithm (chlor_a) employs the standard OC3/OC4 (OCx) band ratio algorithm merged with the color index (CI) of Hu et al. (2012). As described in that paper, this refinement is restricted to relatively clear water, and the general impact is to reduce artifacts and biases in clear-water chlorophyll retrievals due to residual glint, stray light, atmospheric correction errors, and white or spectrally-linear bias errors in Rrs. As implemented, the algorithm diverges slightly from what was published in Hu et al. (2012) in that the transition between CI and OCx now occurs at 0.15 < CI < 0.2 mg/m3 to ensure a smooth transition."
