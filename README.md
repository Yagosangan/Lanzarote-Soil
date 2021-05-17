# Lanzarote-Soil

## Statistical analysis of soil data from the arid island of Lanzarote

This work is part of the final project for the Master's Degree in Bioinformatics and Biostatistics (UOC/UB). It includes an exploratory statistical analysis of more than 600 soil samples extracted from the island of Lanzarote, in the Canarian archipelago, throughout multiple
field campaigns between September 2010 and September 2016. 

The exploration is developed in the R language, saving the whole process in R markdown documents. The document "Lanzarote Soil_Main" contains the principal analysis procedure. It is supported by the functions implemented in "Lanzarote Soil_Functions", which the main document access at the beggining using the "source" command (local path to the file must be manually introduced).

Currently, the principal function is "variable_exploration", which takes the variables of the dataframe one by one and generates a pdf document as its output, containing multiple  exploratory techniques. It is still under development, and will be improved with more tools and commands. The outputs of the function applied to every variable can be found in the "variable_exploration outputs" file.

Nevertheless, the original data is not included due to license reasons, but the knitted HTML documents are contained in the "HTML documents" file.

Author: Yago Sánchez Gancedo
