# The German Regionalized Press Releases Database (GRPR-DB)

 ## Description

This is the data repository for the German Regionalized Press Releases Database (GRPR-DB); i.e., a large collection of press releases from German issuers that have been regionalized at the level of NUTS3 regions. The data is sourced from Presseportal via daily scraping from 10 May 2016 to 31 May 2020. For each press release, the date, keywords, and, if available, locations are reported. The press release and organization IDs are anonymized. Details about the cleaning and geo-location procedures can be found in Ozgun & Broekel (2022).


## Dataset overview


The dataset is in .csv format. The tidy dataset has five columns: ID_PR, ID_ORG, Date, Keywords, and NUTS3. See the table below for further information.


<!-- TABLE_GENERATE_START -->

| Column    | Description									                                             |
| :-------- | :---------------------------------------------------------------------------------------   |
| ID_PR     | Press release ID. Each press release is assigned a unique ID.  				             |
| ID_ORG    | Organization ID. Each organization issuing press releases is assigned a unique ID.        |
| Keywords  | Keywords assigned to the press release. 						                             |
| Date 	    | The date on which the press release is published on the portal, in yyyy-MM-dd format.      |
| NUTS3     | Nomenclature of territorial units for statistics classification code. 				     |

<!-- TABLE_GENERATE_END -->



## Terms of Use

When using the data, please cite the following publication:

```
@article{ozgun2022assesing,
author = {Ozgun, Burcu and Broekel, Tom},
title = {Assessing press releases as a data source for spatial research},
journal = {REGION},
year = {2022}
}
```



## Authors


If you have any further questions about this dataset please contact [Burcu Ozgun](@burcuozgun) (burcuozgun[at]uni-kassel[dot]de) or [Tom Broekel](@tombroekel) (tom.brokel[at]uis[dot]no).

