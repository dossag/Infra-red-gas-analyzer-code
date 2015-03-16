The first function handles output files from a LI-820 to generate 
a dataframe of the sample details (file name, date-time, slope (k),
mean temperature (of the optical path) and mean pressure. Note that
the temperature measured by the LI-820 is that across the optical 
path and is not appropriate for calculating the CO2 efflux. The 
temperature of the system must be measured separately. The second
and third functions calculate CO2 efflux according to eqns 7 and 9,
respectively.