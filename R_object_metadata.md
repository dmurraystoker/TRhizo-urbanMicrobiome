R Object Metadata
================
David Murray-Stoker


# TRhizo-urbanMicrobiome

Updated: 15 May 2024

Metadata for the R objects associated with the manuscript:

Murray-Stoker, D., L. Rossi and M. T. J. Johnson. Diversity and assembly of the microbiome of a leguminous plant along an urbanization gradient.



# Metadata


## File = alpha\_diversity\_data.rds

| Variable   | Description                                             |
|:-----------|:--------------------------------------------------------|
| Sequence\_ID | Unique sample identifier |
| Population | Source population of the sample |
| Compartment | Compartment (i.e., root or soil) to which the sample belongs |
| Replicate | Replicate number within the population |
| DNA\_Concentration | Concentration of raw extracted DNA (ng/uL) |
| Usable\_Reads | Number of usable reads for that sample |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient |
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient |
| Distance | Distance from the city centre to the source population of the sample |
| Human\_Influence\_Index | Index value for the source population of the sample |
| Mean\_ISC | Mean percent of impervious surface cover within 500 m of the source population of the sample |
| Richness | Number of unique ASVs in the sample |
| Inverse\_Simpson | Inverse Simpson's index (Simpson's D-1)  for the sample |
| Evenness | Richness divided by Simpson's D-1 for the sample |
| Faiths\_PD | Faith's phylogenetic diversity for the sample |



## File = BC\_PCoA.rds

Principal coordinates analysis (PCoA) for the root and soil microbiomes using the Bray-Curtis distance.



## File = ecosystem\_function\_bacteria\_data.rds

| Variable   | Description                                             |
|:-----------|:--------------------------------------------------------|
| Population | Source population of the sample |
| Compartment | Compartment (i.e., root or soil) to which the sample belongs |
| *\_Abundance | Number of reads assigned to bacteria in that genus for all samples in the population |
| *\_Relative\_Abundance | Proportion of reads assigned to bacteria in that genus for all samples in the population |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient |
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient |
| Distance | Distance from the city centre to the source population of the sample |
| Human\_Influence\_Index | Index value for the source population of the sample |
| Mean\_ISC | Mean percent of impervious surface cover within 500 m of the source population of the sample |



## File = microbiome\_phyloseq\_reference.rds

Reference `phyloseq` object with both root and soil sequences and associated sample data. Generated in the [phyloseq processing](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/04-phyloseq_processing) script after potential contaminant sequences were removed. Used to analyzed [diversity and composition](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/07-diversity_composition_analyses), [differential abundance](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/09-differential_abundance), and [bacterial functional groups](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/10-bacterial_functional_groups).



## File = microbiome\_pSEM\_data.rds

| Variable   | Description                                             |
|:-----------|:--------------------------------------------------------|
| Population | Source population of the sample |
| Root\_BC\_PCoA\_1 | Mean value on PCoA axis 1 for the root sample (Bray-Curtis distance) |
| Root\_BC\_PCoA\_2 | Mean value on PCoA axis 2 for the root sample (Bray-Curtis distance) |
| Root\_UniFrac\_PCoA\_1 | Mean value on PCoA axis 1 for the root sample (UniFrac distance) |
| Root\_UniFrac\_PCoA\_2 | Mean value on PCoA axis 2 for the root sample (UniFrac distance) |
| Root\_Weighted\_UniFrac\_PCoA\_1 | Mean value on PCoA axis 1 for the root sample (weighted UniFrac distance) |
| Root\_Weighted\_UniFrac\_PCoA\_2 | Mean value on PCoA axis 2 for the root sample (weighted UniFrac distance) |
| Soil\_BC\_PCoA\_1 | Mean value on PCoA axis 1 for the soil sample (Bray-Curtis distance) |
| Soil\_BC\_PCoA\_2 | Mean value on PCoA axis 2 for the soil sample (Bray-Curtis distance) |
| Soil\_UniFrac\_PCoA\_1 | Mean value on PCoA axis 1 for the soil sample (UniFrac distance) |
| Soil\_UniFrac\_PCoA\_2 | Mean value on PCoA axis 2 for the soil sample (UniFrac distance) |
| Soil\_Weighted\_UniFrac\_PCoA\_1 | Mean value on PCoA axis 1 for the soil sample (weighted UniFrac distance) |
| Soil\_Weighted\_UniFrac\_PCoA\_2 | Mean value on PCoA axis 2 for the soil sample (weighted UniFrac distance) |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient |
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient |
| Distance | Distance from the city centre to the source population of the sample |
| Human\_Influence\_Index | Index value for the source population of the sample |
| Mean\_ISC | Mean percent of impervious surface cover within 500 m of the source population of the sample |
| Soil\_Total\_Carbon | Amount of the soil sample that was carbon (\%) | Numeric |
| Soil\_Delta\_13C | Ratio of 13:12 carbon in the soil sample | Numeric |
| Leaf\_Total\_Carbon | Amount of the leaf sample that was carbon (\%) | Numeric |
| Leaf\_Delta\_13C | Ratio of 13:12 carbon in the leaf sample | Numeric |
| Soil\_Total\_Nitrogen | Amount of the soil sample that was nitrogen (\%) | Numeric |
| Soil\_Delta\_15N | Ratio of 15:14 nitrogen in the soil sample | Numeric |
| Leaf\_Total\_Nitrogen | Amount of the leaf sample that was nitrogen (\%) | Numeric |
| Leaf\_Delta\_15N | Ratio of 15:14 nitrogen in the leaf sample | Numeric |



## File = microbiome\_tidyamplicon\_reference.rds

Reference `tidyamplicons` object converted from `microbiome_phyloseq_reference.rds`. Used to analyzed [diversity and composition](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/07-diversity_composition_analyses), [differential abundance](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/09-differential_abundance), and [bacterial functional groups](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/10-bacterial_functional_groups).



## File = multivariate\_dispersion\_data.rds

| Variable   | Description                                             |
|:-----------|:--------------------------------------------------------|
| Population | Source population of the sample |
| Compartment | Compartment (i.e., root or soil) to which the sample belongs |
| Mean\_BC\_Dispersion | Mean distance to the centroid for all sample in the population (Bray-Curtis distance) |
| Mean\_UniFrac\_Dispersion | Mean distance to the centroid for all sample in the population (UniFranc distance) |
| Mean\_Weighted\_UniFrac\_Dispersion | Mean distance to the centroid for all sample in the population (weighted UniFranc distance) |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient |
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient |
| Distance | Distance from the city centre to the source population of the sample |
| Human\_Influence\_Index | Index value for the source population of the sample |
| Mean\_ISC | Mean percent of impervious surface cover within 500 m of the source population of the sample |



## File = mutualistic\_bacteria\_data.rds

| Variable   | Description                                             |
|:-----------|:--------------------------------------------------------|
| Population | Source population of the sample |
| Compartment | Compartment (i.e., root or soil) to which the sample belongs |
| *\_Abundance | Number of reads assigned to bacteria in that genus for all samples in the population |
| *\_Relative\_Abundance | Proportion of reads assigned to bacteria in that genus for all samples in the population |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient |
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient |
| Distance | Distance from the city centre to the source population of the sample |
| Human\_Influence\_Index | Index value for the source population of the sample |
| Mean\_ISC | Mean percent of impervious surface cover within 500 m of the source population of the sample |



## File = pathogenic\_bacteria\_data.rds

| Variable   | Description                                             |
|:-----------|:--------------------------------------------------------|
| Population | Source population of the sample |
| Compartment | Compartment (i.e., root or soil) to which the sample belongs |
| *\_Abundance | Number of reads assigned to bacteria in that genus for all samples in the population |
| *\_Relative\_Abundance | Proportion of reads assigned to bacteria in that genus for all samples in the population |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient |
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient |
| Distance | Distance from the city centre to the source population of the sample |
| Human\_Influence\_Index | Index value for the source population of the sample |
| Mean\_ISC | Mean percent of impervious surface cover within 500 m of the source population of the sample |



## File = root\_decontam\_phyloseq\_reference.rds

`phyloseq` object for the root samples following the DADA2 pipeline and generated in the subsequent [phyloseq processing](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/04-phyloseq_processing).



## File = root\_tidyamplicon\_reference.rds

Reference `tidyamplicons` object converted from `root_decontam_phyloseq_reference.rds` after the root samples were rarefied.



## File = soil\_decontam\_phyloseq\_reference.rds

`phyloseq` object for the soil samples following the DADA2 pipeline and generated in the subsequent [phyloseq processing](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/04-phyloseq_processing).



## File = soil\_tidyamplicon\_reference.rds

Reference `tidyamplicons` object converted from `soil_decontam_phyloseq_reference.rds` after the soil samples were rarefied.



## File = UniFrac\_PCoA.rds

Principal coordinates analysis (PCoA) for the root and soil microbiomes using the UniFrac distance.



## File = urbanization\_data.rds

| Variable   | Description                                             |
|:-----------|:--------------------------------------------------------|
| Population | Source population of the sample |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient |
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient |
| Distance | Distance from the city centre to the source population of the sample |
| Human\_Influence\_Index | Index value for the source population of the sample |
| Mean\_ISC | Mean percent of impervious surface cover within 500 m of the source population of the sample |



## File = weighted\_UniFrac\_PCoA.rds

Principal coordinates analysis (PCoA) for the root and soil microbiomes using the weighted UniFrac distance.
