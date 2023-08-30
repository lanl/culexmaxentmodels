# culexmaxentmodels

netCDF files of *Culex* mosquito habitat suitability values

## Title:
Updated distribution maps of predominant Culex mosquitoes across the Americas

## Authors: 
Morgan E. Gorris<sup>1</sup>, Andrew W. Bartlow<sup>2</sup>, Seth D. Temple<sup>3,4</sup>, Daniel Romero-Alvarez<sup>1,5,6</sup>, Deborah P. Shutt<sup>1</sup>, Jeanne M. Fair<sup>2</sup>, Kimberly A. Kaufeld<sup>3</sup>, Sara Y. Del Valle<sup>1</sup>, Carrie A. Manore<sup>1</sup>

## Affiliations: 
1.	Information Systems and Modeling, Los Alamos National Laboratory, Los Alamos, NM, USA
2.	Biosecurity and Public Health, Los Alamos National Laboratory, Los Alamos, NM, USA
3.	Statistical Sciences, Los Alamos National Laboratory, Los Alamos, NM, USA 
4.	Department of Statistics, University of Washington, Seattle, WA, USA
5.	Biodiversity Institute and Department of Ecology & Evolutionary Biology, University of Kansas, Lawrence, KS, USA
6.	OneHealth Research Group, Facultad de Ciencias de la Salud, Universidad de las Américas, Quito, Ecuador

## Contact information:
Morgan Gorris, mgorris@lanl.gov

# Description: 
This repository contains seven netCDF files with habitat suitability values from 0-1 for *Culex* mosquito species across the Americas: *C. erraticus**, *C. nigripalpus**, *C. pipiens*, *C. quinquefasciatus**, *C. restuans*, *C. salinarius*, and *C. tarsalis*. These maps are the mean habitat suitability averaged across 10 bootstrapped Maxent models.

*Habitat suitability values for these species are available for both North and South America. The remainder are available for only North America. 

Each netCDF file is less than or up to 1.2 MB in size. 

The paper associated with this dataset is: 
Gorris, M.E., Bartlow, A.W., Temple, S.D. et al. Updated distribution maps of predominant Culex mosquitoes across the Americas. Parasites Vectors 14, 547 (2021). [https://doi.org/10.1186/s13071-021-05051-3]

## netCDF files:
Each netCDF files contains the following three variables:<br />
<br />
**longitude:** 1-dimensional array of longitude values  <br />
**latitude:** 1-dimensional array of latitude values<br />
**layer:** 2-dimensional array, the size of latitude by longitude, containing the habitat suitability values from 0-1. <br />

## LA-UR:
This repository is approved for public release under LA-UR-21-24576.
