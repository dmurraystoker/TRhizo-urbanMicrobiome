R Object Metadata
================
David Murray-Stoker


# TRhizo-urbanMicrobiome

Updated: 15 May 2024

Metadata for the R objects associated with the manuscript:

Murray-Stoker, D., L. Rossi and M. T. J. Johnson. Diversity and assembly of the microbiome of a leguminous plant along an urbanization gradient.



# Metadata


## File = alpha_diversity_data.rds

| Variable   | Description                                             |
|:-----------|:--------------------------------------------------------|
| Sequence_ID | Unique sample identifier |
| Population | Source population of the sample |
| Compartment | Compartment (i.e., root or soil) to which the sample belongs |
| Replicate | Replicate number within the population |
| DNA_Concentration | Concentration of raw extracted DNA (ng/uL) |
| Usable_Reads | Number of usable reads for that sample |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient |
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient |
| Distance | Distance from the city centre to the source population of the sample |
| Human_Influence_Index | Index value for the source population of the sample |
| Mean_ISC | Mean percent of impervious surface cover within 500 m of the source population of the sample |
| Richness | Number of unique ASVs in the sample |
| Inverse_Simpson | Inverse Simpson's index (Simpson's D-1)  for the sample |
| Evenness | Richness divided by Simpson's D-1 for the sample |
| Faiths_PD | Faith's phylogenetic diversity for the sample |



## File = BC_PCoA.rds

Principal coordinates analysis (PCoA) for the root and soil microbiomes using the Bray-Curtis distance.



## File = ecosystem_function_bacteria_data.rds

| Variable   | Description                                             |
|:-----------|:--------------------------------------------------------|
| Population | Source population of the sample |
| Compartment | Compartment (i.e., root or soil) to which the sample belongs |
| *_Abundance | Number of reads assigned to bacteria in that genus for all samples in the population |
| *_Relative_Abundance | Proportion of reads assigned to bacteria in that genus for all samples in the population |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient |
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient |
| Distance | Distance from the city centre to the source population of the sample |
| Human_Influence_Index | Index value for the source population of the sample |
| Mean_ISC | Mean percent of impervious surface cover within 500 m of the source population of the sample |



## File = microbiome_phyloseq_reference.rds

Reference `phyloseq` object with both root and soil sequences and associated sample data. Generated in the [phyloseq processing](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/04-phyloseq_processing) script after potential contaminant sequences were removed. Used to analyzed [diversity and composition](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/07-diversity_composition_analyses), [differential abundance](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/09-differential_abundance), and [bacterial functional groups](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/10-bacterial_functional_groups).



## File = microbiome_pSEM_data.rds

| Variable   | Description                                             |
|:-----------|:--------------------------------------------------------|
| Population | Source population of the sample |
| Root_BC_PCoA_1 | Mean value on PCoA axis 1 for the root sample (Bray-Curtis distance) |
| Root_BC_PCoA_2 | Mean value on PCoA axis 2 for the root sample (Bray-Curtis distance) |
| Root_UniFrac_PCoA_1 | Mean value on PCoA axis 1 for the root sample (UniFrac distance) |
| Root_UniFrac_PCoA_2 | Mean value on PCoA axis 2 for the root sample (UniFrac distance) |
| Root_Weighted_UniFrac_PCoA_1 | Mean value on PCoA axis 1 for the root sample (weighted UniFrac distance) |
| Root_Weighted_UniFrac_PCoA_2 | Mean value on PCoA axis 2 for the root sample (weighted UniFrac distance) |
| Soil_BC_PCoA_1 | Mean value on PCoA axis 1 for the soil sample (Bray-Curtis distance) |
| Soil_BC_PCoA_2 | Mean value on PCoA axis 2 for the soil sample (Bray-Curtis distance) |
| Soil_UniFrac_PCoA_1 | Mean value on PCoA axis 1 for the soil sample (UniFrac distance) |
| Soil_UniFrac_PCoA_2 | Mean value on PCoA axis 2 for the soil sample (UniFrac distance) |
| Soil_Weighted_UniFrac_PCoA_1 | Mean value on PCoA axis 1 for the soil sample (weighted UniFrac distance) |
| Soil_Weighted_UniFrac_PCoA_2 | Mean value on PCoA axis 2 for the soil sample (weighted UniFrac distance) |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient |
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient |
| Distance | Distance from the city centre to the source population of the sample |
| Human_Influence_Index | Index value for the source population of the sample |
| Mean_ISC | Mean percent of impervious surface cover within 500 m of the source population of the sample |
| Soil_Total_Carbon | Amount of the soil sample that was carbon (\%) | Numeric |
| Soil_Delta_13C | Ratio of 13:12 carbon in the soil sample | Numeric |
| Leaf_Total_Carbon | Amount of the leaf sample that was carbon (\%) | Numeric |
| Leaf_Delta_13C | Ratio of 13:12 carbon in the leaf sample | Numeric |
| Soil_Total_Nitrogen | Amount of the soil sample that was nitrogen (\%) | Numeric |
| Soil_Delta_15N | Ratio of 15:14 nitrogen in the soil sample | Numeric |
| Leaf_Total_Nitrogen | Amount of the leaf sample that was nitrogen (\%) | Numeric |
| Leaf_Delta_15N | Ratio of 15:14 nitrogen in the leaf sample | Numeric |



## File = microbiome_tidyamplicon_reference.rds

Reference `tidyamplicons` object converted from `microbiome_phyloseq_reference.rds`. Used to analyzed [diversity and composition](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/07-diversity_composition_analyses), [differential abundance](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/09-differential_abundance), and [bacterial functional groups](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/10-bacterial_functional_groups).



## File = multivariate_dispersion_data.rds

| Variable   | Description                                             |
|:-----------|:--------------------------------------------------------|
| Population | Source population of the sample |
| Compartment | Compartment (i.e., root or soil) to which the sample belongs |
| Mean_BC_Dispersion | Mean distance to the centroid for all sample in the population (Bray-Curtis distance) |
| Mean_UniFrac_Dispersion | Mean distance to the centroid for all sample in the population (UniFranc distance) |
| Mean_Weighted_UniFrac_Dispersion | Mean distance to the centroid for all sample in the population (weighted UniFranc distance) |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient |
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient |
| Distance | Distance from the city centre to the source population of the sample |
| Human_Influence_Index | Index value for the source population of the sample |
| Mean_ISC | Mean percent of impervious surface cover within 500 m of the source population of the sample |



## File = mutualistic_bacteria_data.rds

| Variable   | Description                                             |
|:-----------|:--------------------------------------------------------|
| Population | Source population of the sample |
| Compartment | Compartment (i.e., root or soil) to which the sample belongs |
| *_Abundance | Number of reads assigned to bacteria in that genus for all samples in the population |
| *_Relative_Abundance | Proportion of reads assigned to bacteria in that genus for all samples in the population |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient |
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient |
| Distance | Distance from the city centre to the source population of the sample |
| Human_Influence_Index | Index value for the source population of the sample |
| Mean_ISC | Mean percent of impervious surface cover within 500 m of the source population of the sample |



## File = pathogenic_bacteria_data.rds

| Variable   | Description                                             |
|:-----------|:--------------------------------------------------------|
| Population | Source population of the sample |
| Compartment | Compartment (i.e., root or soil) to which the sample belongs |
| *_Abundance | Number of reads assigned to bacteria in that genus for all samples in the population |
| *_Relative_Abundance | Proportion of reads assigned to bacteria in that genus for all samples in the population |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient |
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient |
| Distance | Distance from the city centre to the source population of the sample |
| Human_Influence_Index | Index value for the source population of the sample |
| Mean_ISC | Mean percent of impervious surface cover within 500 m of the source population of the sample |



## File = root_decontam_phyloseq_reference.rds

`phyloseq` object for the root samples following the DADA2 pipeline and generated in the subsequent [phyloseq processing](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/04-phyloseq_processing).



## File = root_tidyamplicon_reference.rds

Reference `tidyamplicons` object converted from `root_decontam_phyloseq_reference.rds` after the root samples were rarefied.



## File = soil_decontam_phyloseq_reference.rds

`phyloseq` object for the soil samples following the DADA2 pipeline and generated in the subsequent [phyloseq processing](https://github.com/dmurraystoker/TRhizo-urbanMicrobiome/tree/main/data_analysis/04-phyloseq_processing).



## File = soil_tidyamplicon_reference.rds

Reference `tidyamplicons` object converted from `soil_decontam_phyloseq_reference.rds` after the soil samples were rarefied.



## File = UniFrac_PCoA.rds

Principal coordinates analysis (PCoA) for the root and soil microbiomes using the UniFrac distance.



## File = urbanization_data.rds

| Variable   | Description                                             |
|:-----------|:--------------------------------------------------------|
| Population | Source population of the sample |
| Latitude | Latitude (decimal degrees) of the population along the urbanization gradient |
| Longitude | Longitude (decimal degrees) of the population along the urbanization gradient |
| Distance | Distance from the city centre to the source population of the sample |
| Human_Influence_Index | Index value for the source population of the sample |
| Mean_ISC | Mean percent of impervious surface cover within 500 m of the source population of the sample |



## File = weighted_UniFrac_PCoA.rds

Principal coordinates analysis (PCoA) for the root and soil microbiomes using the weighted UniFrac distance.
