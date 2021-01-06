## Data files for COMM318 _Stories from data_ Final Project

* This folder should contain the data files you have used in your analysis


* You should update this README file to list and describe the files.


* You can also create additional sub-folders to better organize your data.
    * For example, you could have a folder called `raw` or `orig` to contain the original data files you downloaded and then a folder called `final` or `clean` that contains versions of these data sheets that you have worked with to clean up missing data, to subset or merge etc.
    
#### Data file

* `dataframe.csv` - Cleaned and merged statistics by county fips code
* `dataframe_onehot.csv` - dataframe.csv but with selected statistics and urbanization split into one hot classification
* `fips.csv` - Association of all FIPS codes with locations
* `raw` - Folder for all raw data
    * `county_broadband_adoption.csv` - Broadband adoption by county over time 
    * `Education.csv` - education statistics by county
    * `population_estimates.csv` - population and migration by county (unused in favor of urban_rural_classification)
    * `poverty_estimates.csv` - poverty statistics by county
    * `Unemployment.csv` - unemployment statistics by county
    * `urban_rural_classification.csv`- county classifications of urbanization