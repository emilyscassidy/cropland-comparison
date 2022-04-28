# Comparing Commonly-Used Crop Maps of Crop Harvested Area


## Purpose of the Project

Researchers need reliable crop maps to understand how agricultural extent is changing over time. These maps help inform governments about how land use might change with growing food demands. 

This project will provide a reproducible way to compare crop extent maps, with the output being a map of the differences between two maps and a spreadsheet of differences within subnational regions. By creating a reproducible method of comparing different crop maps, this research will improve transparency around agricultural research. 

## Installation instructions 

This code should work if you have the latest version of either Miniconda or Anaconda Python packages installed on your computer.
For instructions for how to set that up, follow the CU Boulder Earth Data Analytics instructions for setting up [Python, Git, Bash Environment On Your Computer](https://www.earthdatascience.org/workshops/setup-earth-analytics-python/setup-git-bash-conda/).


## Data Used

This code compares crop-specific cropland maps from:

1. [Earthstat](http://www.earthstat.org/), a data collection developed by researchers at the University of Minnesota and University of British Colombia (and formerly the University of Wisconsin, Madison). The crop-specific maps can be found at [earthstat.org/harvested-area-yield-175-crops](http://www.earthstat.org/harvested-area-yield-175-crops/)
The data citation is: 
Monfreda, C., N. Ramankutty, and J. A. Foley (2008), Farming the planet: 2. Geographic distribution of crop areas, yields, physiological types, and net primary production in the year 2000, Global Biogeochem. Cycles, 22, GB1022, doi: 10.1029/2007GB002947.

2. [MapSPAM](https://www.mapspam.info/data/) data from the International Food Policy Research Institute (IFRPI) and Harvard University. Their SPAM 2000 v3.0.7 Global Data from 2019 was used. 
The citation for this data is: 
International Food Policy Research Institute, 2019, “Global Spatially-Disaggregated Crop Production Statistics Data for 2000 Version 3.0.7”, https://doi.org/10.7910/DVN/A50I2T, Harvard Dataverse, V1.


## Workflow
Goal: Develop a resource to compare crop maps from different sources.

A breif summary of the code workflow is below.

<img width="867" alt="Cropland Comparison workflow" src="https://user-images.githubusercontent.com/58826433/165811524-2c07475a-d1d9-410e-a348-f765d0307e0a.png">

