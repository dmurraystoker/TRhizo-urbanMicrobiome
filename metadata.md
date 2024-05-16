Metadata
================
David Murray-Stoker


# TRhizo-urbanMicrobiome

Updated: 15 May 2024

Metadata for the primary data files associated with the manuscript:

Murray-Stoker, D., L. Rossi and M. T. J. Johnson. Diversity and assembly of the microbiome of a leguminous plant along an urbanization gradient.


# Metadata

## Raw Data

Stored in the [raw_data](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/raw_data) folder.


### file = TRhizo-urbanMicrobiome-sample\_data.xlsx

**Roots** Sheet = identifiers and covariates for root DNA samples

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Sequence\_ID | Unique sample identifier | Character |
| Population | Source population of the sample | Character |
| Replicate | Replicate number within the population | Integer |
| Total\_Nodules | Number of nodules on the collected roots | Integer |
| Root\_Mass | Total collected root biomass (g) | Numeric |
| Standardized\_Nodules | Total number of nodules divided by collected root biomass; Total\_Nodules / Root\_Mass | Numeric |
| DNA\_Concentration | Concentration of raw extracted DNA (ng/uL) | Numeric |


**Soil** Sheet = identifiers and covariates for soil DNA samples

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Sequence\_ID | Unique sample identifier | Character |
| Population | Source population of the sample | Character |
| Replicate | Replicate number within the population | Integer |
| Soil\_Mass | Total collected root biomass (g) | Numeric |
| DNA\_Concentration | Concentration of raw extracted DNA (ng/uL) | Numeric |


**Microbiome** sheet = combined sheet with identifiers for all root and soil samples

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Sequence\_ID | Unique sample identifier | Character |
| Population | Source population of the sample | Character |
| Compartment | Compartment (i.e., root or soil) to which the sample belongs | Character |
| Replicate | Replicate number within the population | Integer |
| DNA\_Concentration | Concentration of raw extracted DNA (ng/uL) | Numeric |



### file = TRhizo-urbanMicrobiome-site\_information.xlsx

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Population | Population to which the information corresponds | Character |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient | Numeric | 
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient | Numeric |



### file = TRhizo-urbanMicrobiome-carbon\_nitrogen\_data

**Carbon** Sheet = identifiers and covariates for root DNA samples

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Population | Source population of the sample | Character |
| Soil\_Sample\_Weight | Weight of the soil sample (g) | Numeric |
| Soil\_Total\_Carbon | Amount of the soil sample that was carbon (\%) | Numeric |
| Soil\_Delta\_13C | Ratio of 13:12 carbon in the soil sample | Numeric |
| Leaf\_Sample\_Weight | Weight of the leaf sample (g) | Numeric |
| Leaf\_Total\_Carbon | Amount of the leaf sample that was carbon (\%) | Numeric |
| Leaf\_Delta\_13C | Ratio of 13:12 carbon in the leaf sample | Numeric |


**Nitrogen** Sheet = identifiers and covariates for soil DNA samples

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Population | Source population of the sample | Character |
| Soil\_Sample\_Weight | Weight of the soil sample (g) | Numeric |
| Soil\_Total\_Nitrogen | Amount of the soil sample that was nitrogen (\%) | Numeric |
| Soil\_Delta\_15N | Ratio of 15:14 nitrogen in the soil sample | Numeric |
| Leaf\_Sample\_Weight | Weight of the leaf sample (g) | Numeric |
| Leaf\_Total\_Nitrogen | Amount of the leaf sample that was nitrogen (\%) | Numeric |
| Leaf\_Delta\_15N | Ratio of 15:14 nitrogen in the leaf sample | Numeric |





## Cleaned Data

Stored in the [data](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data) folder.


### file = urbanMicrobiome-sample\_data-microbiome.csv

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Sequence\_ID | Unique sample identifier | Character |
| Population | Source population of the sample | Character |
| Compartment | Compartment (i.e., root or soil) to which the sample belongs | Character |
| Replicate | Replicate number within the population | Integer |
| DNA\_Concentration | Concentration of raw extracted DNA (ng/uL) | Numeric |



### file = urbanMicrobiome-site\_information.csv

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Population | Population to which the information corresponds | Character |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient | Numeric | 
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient | Numeric |



### file = urbanMicrobiome-carbon\_data.csv

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Population | Source population of the sample | Character |
| Soil\_Total\_Carbon | Amount of the soil sample that was carbon (\%) | Numeric |
| Soil\_Delta\_13C | Ratio of 13:12 carbon in the soil sample | Numeric |
| Leaf\_Total\_Carbon | Amount of the leaf sample that was carbon (\%) | Numeric |
| Leaf\_Delta\_13C | Ratio of 13:12 carbon in the leaf sample | Numeric |
  


### file = urbanMicrobiome-nitrogen\_data.csv

| Variable   | Description                                             | Type      | 
|:-----------|:--------------------------------------------------------|:----------|
| Population | Source population of the sample | Character |
| Soil\_Total\_Nitrogen | Amount of the soil sample that was nitrogen (\%) | Numeric |
| Soil\_Delta\_15N | Ratio of 15:14 nitrogen in the soil sample | Numeric |
| Leaf\_Total\_Nitrogen | Amount of the leaf sample that was nitrogen (\%) | Numeric |
| Leaf\_Delta\_15N | Ratio of 15:14 nitrogen in the leaf sample | Numeric |
