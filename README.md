# INFM600
This is the  dataset created for the INFM600 Information Discovery and Analysis Assignment
-------
Version
-------

Version 1.0 (March 2016)

-----------
Description
-----------

**Focal Data** http://catalog.data.gov/dataset/2010-census-populations-by-zip-code

**2010_Census_Populations_by_Zip_Code.csv**

This file includes data about Census Profile of General Population and Housing Characteristics held in 2010. In this dataset, zip codes are limited to those that fall at least partially within LA city boundaries. This dataset includes important details such as Zip Code, Total Population, Median age, Total Males, Total Females, Total Households, Average Household Size.

**Supporting Data Sets**

**Water_Use_Average_By_Zipcode.csv**

This data set includes information about the residential water use by month averaged for fiscal year. The values in the dataset represent Hundred Cubic Feet (HCF) of water use. It has data values describing water consumption for eight fiscal years from 2005 to 2013 and zip code of LA city boundaries.

**Average_monthly_residential_energy_usage_By_zip_code.csv**

This data set includes information about the residential energy use (averaged monthly) for each fiscal year since 2003 in kilowatt hours (kWh). It has data values describing energy consumption for eight fiscal years from 2005 to 2013 and zip code of LA city boundaries.

**Merged Dataset**

**Resource_Usage_By_Zipcode.csv**

This data set uses the data from the focal data set and the supporting datasets. It consists values of energy and water consumption linked together by zip codes which are of LA city boundaries. The average of water consumption and energy consumption of eight fiscal years is determined and compared against the various age groups residing in different zip code areas of LA.

---------------
Analysis
---------------
We merged the focal dataset () with the two additional datasets on zipcodes. The process documentation for merger can be found in "Workflow Documentation.pdf"

**Do areas having median age under 30 are likely to consume more water and residential energy than other age gropus?**

We viewed all the three datasets taken from data.gov and merged it to a single one.
On basis of median age provided for each zipcodes, we proposed that age might be a factor affecting energy and water consumption of LA city boundaries. 

Average Usage of Residential Energy

![alt tag](https://github.com/manujakaushal/INFM600/blob/master/Average_Energy_Usage.jpg)

Average Usage of Water

![alt tag](https://github.com/manujakaushal/INFM600/blob/master/Average_Water_Usage.jpg)
-----
Files
-----

*Water Use Average By Zipcode*

*Average Monthly Residential Energy Usage By Zipcode*

*2010 Census Populations By Zipcode*

*Resource_Usage_By_Zipcode*

*Workflow Documentation*

------- 
License
-------

The data in the INFM600 repository is distributed under a Creative Commons 
Attribution-NonCommercial-ShareAlike 4.0 International License (see 
http://creativecommons.org/licenses/by-nc-sa/4.0/).

The data including Water Use Average By Zipcode, Average Monthly Residential Energy Usage By Zipcode, 2010 Census Populations By Zipcode is made available for public access and use. 

The data 'Resource_Usage_By_Zipcode' is made available for non-commercial use. Those interested in using the data in a commercial context should contact the owners(Chinmay Raote, Manuja Kaushal)

----------------
Acknowledgements
----------------

   We thank the Data.Gov for providing valuable datasets such as Water Use Average, Average Monthly Residential Energy Usage, 2010 Census Populations by Zipcode.
   
   We thank the GroupLens research group at the University of Minnesota (http://www.grouplens.org) for hosting and allowing use of the MovieLens10M dataset in the master dataset and Iván Cantador, Alejandro Bellogín and Ignacio Fernández-Tobías and the Information Retrieval group at Universidad Autonoma de Madrid (http://ir.ii.uam.es) for creating and releasing the master data set.



----------
References
----------

Data.gov City of Los Angeles (2016) Water Use Average By Zipcode [Data set CSV file]. Retrieved from http://catalog.data.gov/dataset/water-use-average-by-zipcode-8dbe0. March 18, 2016

Data.gov City of Los Angeles (2016) Average Monthly Residential Energy Usage By Zipcode [Data set CSV file]. Retrieved from http://catalog.data.gov/dataset/average-monthly-residential-energy-usage-by-zip-code-0487d. March 18, 2016

Data.gov City of Los Angeles (2016) 2010 Census Populations By Zipcode [Data set CSV file]. Retrieved from http://catalog.data.gov/dataset/2010-census-populations-by-zip-code. March 18, 2016

Raote, C., Kaushal, M. (2015). Resource_Usage_By_Zipcode [Data CSV file]. Available from https://github.com/manujakaushal/INFM600/blob/master/Resource_Usage_By_Zipcode.csv.

-------
Credits
-------

Chinmay Raote
</br>Manuja Kaushal
