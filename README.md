# covid_WI_inland_fishing
The effects of the COVID-19 pandemic on fishing effort on northern inland WI lakes
Code and data comparing vehicle coutns in 2018, 2019, and 2020 at 38 lakes in Vilas County, WI. 

Code: revisions.analysis.Rmd

Old version: vehicle.count.analysis.Rmd

Code reads data from 'data for analysis' and 'lakevar' folders. 
Files:
data for analysis folder 
- boatSamples.IS.csv: Sampling event data for boat-based instantaneous counts of fishing effort in 2018 and 2019. 
- CREEL_POINT_BOATCOUNT.csv: Count data for boat-based instantaneous counts. Used to compare fraction of boats fishing vs. not fishing in 2020 and years previous.
- data.2018.2019.collapsed.new.col.csv: Trailer count data from 2018 and 2019. Column has been manually added that adds non-fishing vehicles to fishing vehicles observed at access points. 
- sample.events.update.20200727.csv: Trailer count data from 2020.
- trailerSamplesIS.csv: Trailer count data from 2018 and 2019 before aggregate vehicle column has been added. 

lakevar folder
- FS_lakes.csv: lakes surveyed in 2018 and 2019
-FS_lakes_camping.csv: Campground presence at lakes surveyed in 2018 and 2019
- ShorelineDevelopment_Vilas_03-15-2018.csv: building density around shorelines of all lakes surveyed
- vilasCounty_boatLaunchsMFEdb.csv: Access point characteristics of all Vilas County public access lakes
- vilasLakes.csv: Lake size, access, species presence, and lake type pulled from WDNR Wisconsin Lakes database
- lake order char.csv: added 8/30/2022, includes proportion of shoreline public lands

Code writes to exploratory plots and figures folders

Code comparing license sales in 2020 to previous 5 years. 

license.data.Rmd
(For aggregate license sales data, contact Ben Beardmore: Alan.Beardmore(at)wisconsin.gov)
Pulls from license sales data, writes to figures folder.
