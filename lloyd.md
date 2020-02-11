# Reading Response 2
Theresa Reese

February 10, 2020
## Lloyd et al.
[High resolution global gridded data for use in population studies](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5283062/) Scientific Data: Jan. 2017

## Question
Perspective Question: In the Lloyd et al. article, the authors introduce a method that uses a number of different openly available geospatial datasets in order to produce high resolution, global gridded descriptions of human populations. Describe the geospatial datasets the authors are using in their methodology. How is their method an improvement when compared to a conventional census? Are you able to describe how the authors use a number of different geospatial layers with their data science method in order to produce a high resolution, global gridded description of human population?

## Response
The datasets the authors are using include raster topography data from the Viewfinders Panorama dataset and vector country boundary data and country ids from GADM (as well as GPW). They also incorporated other spatial datasets into the archive, such as annual mean precipitation data, night light intensity data, land cover data, and water body data, meant to be used as covariates for population modelling.

The method is an improvement when compared to a conventional census because it is more cost-effective and incorporating the different spatial datasets can improve the accuracy of the population mapping. 

The authors standardised the Viewfinder Panoramas data set in order to make the topography layer of the archive and derived the slope layer of the archive from that. They used the GADM data for country ID tiles with accurate boundaries. They then incorporate other spatial datasets to make an archive of global gridded spatial datasets that can be used in addition to census data to improve accuracy in population studies. For example, the Random Forests model is a dasymetric modelling approach that uses census data and ancillary datasets to estimate population distribution.


