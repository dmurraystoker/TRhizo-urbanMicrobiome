# TRhizo-urbanMicrobiome

Data, metadata, and R code for “Diversity and assembly of the microbiome of a leguminous plant along an urbanization gradient”
================
David Murray-Stoker

Updated: 15 May 2024

Data, metadata, and R code for reproducing analyses for the manuscript:

Murray-Stoker, D., L. Rossi and M. T. J. Johnson. Diversity and assembly of the microbiome of a leguminous plant along an urbanization gradient.


## Abstract

Interactions between plants and bacterial communities are essential for host physiology and broader ecosystem functioning, but plant-microbiome interactions can be disrupted by environmental change. Urbanization is a dominant driver of anthropogenic disturbance and environmental change, which may alter plant-microbe interactions. Here, we evaluated how urbanization affected the diversity and assembly of soil and white clover (*Trifolium repens*) bacterial communities. We sampled 35 populations of white clover and associated roots and soil along an urbanization gradient. Soil alpha diversity was greater at the urban and rural limits of the gradient and lower in suburban habitats, while root alpha diversity was not influenced by urbanization. Root and soil compartments had distinct compositions, with greater beta diversity for root compared to soil microbiomes. We found that urbanization directly and indirectly soil microbiome assembly, particularly through soil carbon. In contrast, root microbiome assembly was not linked to urbanization, suggesting the host plant acted as an additional filter on microbiome assembly. We also found that key pathogenic bacteria like *Legionella* and *Clostridium* varied in abundance with urbanization, which has implications for human health. Together, our study underscores the importance of examining how urban-driven environmental change alters the ecology and function of soil and root microbiomes.


## Contents

The [R Project](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/blob/main/TRhizo-urbanMicrobiome.Rproj) provides a local relative directory for all data and R code.


### Data

All data and R objects are provided in the [data](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data) folder, with raw data in .xlsx files in the [raw_data](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/raw_data) folder.

There are 4 primary data files from which all analyses and downstream variables were calculated:

* [urbanMicrobiome-sample_data-microbiome.csv](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/blob/main/data/urbanMicrobiome-sample_data-microbiome.csv)
  - Sample identifier for all sequences
* [urbanMicrobiome-site_information.csv](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/blob/main/data/urbanMicrobiome-site_information.csv)
  - Latitude and longitude for each site
* [urbanMicrobiome-carbon_data.csv](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/blob/main/data/urbanMicrobiome-carbon_data.csv)
  - Total and isotope data for soil and leaf tissue carbon
* [urbanMicrobiome-nitrogen_data.csv](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/blob/main/data/urbanMicrobiome-nitrogen_data.csv)
  - Total and isotope data for soil and leaf tissue nitrogen

Metadata associated with these files and the `raw_data` equivalents is provided [here](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/metadata.md).

Metadata associated with the R objects generated during and used for data analysis is provided [here](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/blob/main/R_object_metadata.md).


### Sequences

All raw sequence files are provided on NCBI under the BioProject accession [PRJNA1107685](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1107685).

For ease of reproducibility, download and store the sequences in the [urbanMicrobiome_sequences](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/urbanMicrobiome_sequences) with a separate folder for root and soil sequences.


### Data Analysis

R Markdown code for all data analyses and figure creation are provided in the [data_analysis](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis) folder.


### Using this repository

To use the data and R code for this project:

1. `git clone` this repository or download it as a zip folder
2. Open `R Studio`, go to `file > Open project`, and open the `TRhizo-urbanMicrobiome.Rproj`
R Project associated with this repository.
3. The analyses can be performed by running through the code in [data_analysis](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis).

